---
title: Form Builder - File Components
permalink: faq.form_builder_file.html
sidebar: orbis_sidebar
keywords: file 
toc: false
folder: orbiscrm.faq
---

<div class="panel-group" id="accordion">
    <div class="panel panel-default">
        <div class="panel-heading">
            <h4 class="panel-title">
                <a class="noCrossRef accordion-toggle" data-toggle="collapse" data-parent="#accordion" href="#how-do-i-set-file-upload">
                    How do I set file upload in a form?
                </a>
            </h4>
        </div>
        <div id="how-do-i-set-file-upload" class="panel-collapse collapse noCrossRef">
            <div class="panel-body">
                <ol>
                    <li>Navigate to the <b>Other</b> section
                    </li>
                    <li>Drag and drop the <b>File</b> component
                    </li>
                    <li>Type in the label of the component in the <b style="color: red">Display</b> section 
                        (E.g. <span style="color: dodgerblue; font-style: italic">Passport Scan File</span>)<br>
                        <img src="images/form_builder/file-display.png"><br>
                        <span style="font-style: italic; font-size: smaller">Example Image</span>
                    </li>
                    <li>Navigate to the <b style="color: dodgerblue">File</b> > <b>Storage</b> section
                    </li>
                    <li>Select the <b>Url</b> option
                    </li>
                    <li>Type in <b style="font-style: italic; color: #0F79D0">https://crm.orbisadvisors.com.au/files/upload</b>
                    </li>
                    <li>Scroll down and edit the <b>File Maximum Size</b> from 1GB to a proper size</li>
                    <li>Finally, click the【Save】button to save this file upload component</li>
                </ol>
            </div>
        </div>
    </div>
    <!-- /.panel -->
</div>
<!-- /.panel-group -->

{% include links.html %}
