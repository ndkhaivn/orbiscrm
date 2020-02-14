---
title: Form Builder - Component Operations
permalink: faq.form_builder_component_operations.html
sidebar: orbis_sidebar
keywords: form builder, operations, components, only, display, hide, show, response, configure, previous, duplicate, copy, compulsory, required, unique, must
toc: false
folder: orbiscrm.faq
summary: For more details or technical help, click the <b><a href="https://help.form.io/userguide/" target="_blank">Help</a></b> in the top-right corner of the pop-up window
---

<div class="panel-group" id="accordion">
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-do-i-add-a-component-in-a-form">
                    How do I add a component in a form?
                </a>
            </h4>
        </div>
        <div id="how-do-i-add-a-component-in-a-form" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
                <ol>
                    <li>Navigate to the specific <b>Component</b> from the left sidebar</li>
                    <li><b>Drag</b> and <b>Drop</b> the component to the satisfied area</li>
                    <li>Do more detailed edition for the component in the pop-up window</li>
                </ol>
            </div>
        </div>
    </div>
    <!-- /.panel -->
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-do-i-duplicate-a-component-in-a-form">
                    How do I duplicate(/copy & paste) a component in a form?
                </a>
            </h4>
        </div>
        <div id="how-do-i-duplicate-a-component-in-a-form" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
                <ol>
                    <li>When you are adding or editing a form</li>
                    <li>Hover the mouse to the specific <b>Component</b></li>
                    <li>Click the <b>(Copy)</b> <img src="images/copy_icon.png" style="width: 3%"> icon</li>
                    <li>Click the <b>(Paste Below)</b> <img src="images/paste_below_icon.png" style="width: 3%"> icon</li>
                </ol>
            </div>
        </div>
    </div>
    <!-- /.panel -->
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-do-i-make-a-component-required">
                    How do I make a component become compulsory/required/unique?
                </a>
            </h4>
        </div>
        <div id="how-do-i-make-a-component-required" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
                <ol>
                    <li>Navigate to the <b>Validation</b> section</li>
                    <li>Tick the checkbox of <b>Required</b> or <b>Unique</b> as you need</li>
                </ol>
            </div>
        </div>
    </div>
    <!-- /.panel -->
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-do-i-change-a-component-display-logic">
                    How do I configure a question to only display based on a user’s response to a previous question?
                </a>
            </h4>
        </div>
        <div id="how-do-i-change-a-component-display-logic" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
                <ol>
                    <li>
                        When you want to configure a component <span style="font-style: italic; color: dodgerblue">(E.g. His/her name?)</span> to display based 
                        on the response to a previous radio component <span style="font-style: italic; color: red">(E.g. Are you married?)</span><br>
                        <img src="images/form_builder/radio.png">
                    </li>
                    <li>
                        Firstly, drag and drop a radio component and rename the label in the <b>Display</b> section                      
                    </li>
                    <li>
                        Navigate to the <b>Data</b> > <b>Values</b> section in the pop-up window
                    </li>
                    <li>
                        Fill in the <b>LABEL</b> and <b>VALUE</b> section
                        <span style="font-style: italic">(E.g. Yes(yes); No(no))</span>
                    </li>
                    <li>
                        Click【<b>Save</b>】button to save this radio component
                    </li>
                    <li>
                        Then, drag and drop a <b>Text Field</b> component
                        <img src="images/form_builder/text-field-display.png">
                    </li>
                    <li>
                        Rename the label to <span style="font-style: italic; color: dodgerblue">"His/her name?"</span> in the <b>Display</b> section
                    </li>
                    <li>
                        Tick the checkbox of <b>Hidden</b>
                    </li>
                    <li>
                        Navigate to the <b>Logic</b> section
                        <img src="images/form_builder/text-field-logic.png">
                    </li>
                    <li>Click the【<b>+ Add Logic</b>】button</li>
                    <li>Type in a proper <b>Logic Name</b> for reference (E.g. <span style="font-style: italic">Logic-1</span>)</li>
                    <li>Navigate to the <b>Trigger</b> section
                        <ol>
                            <li><b>Type</b> > <b style="color:red">Simple</b></li>
                            <li><b>When the component from</b> > <b style="color:red">Are you married? (radio1)</b></li>
                            <li><b>Has the value:</b> > <b style="color:red">yes</b></li>
                        </ol>
                    </li>
                    <li>Navigate to the <b>Actions</b> section
                    <li>Click the【<b>+ Add Action</b>】button</li>
                        <ol>
                            <li>Type in a proper <b>Action Name</b> (E.g. <span style="font-style: italic">Action-1</span>)</li>
                            <li><b>Type</b> > <b style="color:red">Property</b></li>
                            <li><b>Component Property</b> > <b style="color:red">Hidden</b></li>
                            <li><b>Set State</b> > <b style="color:red">False</b></li>
                        </ol>
                    </li>
                    <li>Click the【Save Action】button</li>
                    <li>Click the【Save Logic】button</li>
                    <li>Click the【Save】button</li>
                    <li>Finally, test it after saving the form<br>
                        <ul>
                            <li>
                                <img src="images/form_builder/no-for-hidden.png"><br>
                                <span style="font-style: italic; font-size: smaller">Example: No for hidden</span>
                            </li>
                            <li>
                                <img src="images/form_builder/yes-for-shown.png"><br>
                                <span style="font-style: italic; font-size: smaller">Example: Yes for shown</span>
                            </li>
                        </ul>
                    </li>
                </ol>
            </div>
        </div>
    </div>
    <!-- /.panel -->
</div>
<!-- /.panel-group -->

{% include links.html %}
