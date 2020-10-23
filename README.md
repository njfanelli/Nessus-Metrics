<h1 style="text-align: center;">Nessus Month over Month Trending Tool v1</h1>
<h2>How-To Guide</h2>
<ol>
<ol>
<li>Download/Store your Nessus scan reports to a place on your desktop, I labeled mine &ldquo;NESSUS&rdquo;. NOTE: For the tool to work properly you must use the &ldquo;Nessus Parser&rdquo; script developed by Cody Dumont (found here: <a href="http://www.melcara.com/archives/253">http://www.melcara.com/archives/253</a>.&nbsp; This script will put your data in an acceptable format for the Excel file to read.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-NessusParser.png" alt="" /></li>
<li>Browse to the &ldquo;Asset Overview&rdquo; tab of this workbook.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-AssetOverview.png" alt="" /></li>
<li>Click the &ldquo;Import Data&rdquo; button in the top left hand corner.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-Import.png" alt="" /></li>
<li>Browse to the location where you saved your Nessus reports in Step 1, then select a report that you would like to upload. In this step I&rsquo;ve select my January 2016 report you&rsquo;ll need to remember this for the next step.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-Upload.png" alt="" /></li>
<li>Enter the month for which you are importing data for. <em>NOTE: the text you enter my match one of the tabs provided within the workbook.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-UploadName.png" alt="" /></em></li>
<li>Click &ldquo;Yes&rdquo; to the prompt.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-UploadConfirm.png" alt="" /></li>
<li>Click &ldquo;OK&rdquo; to the prompt.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-UploadOK.png" alt="" /></li>
<li>Enter the value &ldquo;2&rdquo; in the field provided, then click &ldquo;OK&rdquo;. <em>NOTE: Option 1 IS NOT CURRENTLY WORKING.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-UploadType.png" alt="" /></em></li>
<li>Click &ldquo;OK&rdquo; to the prompt.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-UploadNow.png" alt="" /></li>
<li>Click &ldquo;OK&rdquo; to the prompt.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-UploadResults.png" alt="" /></li>
<li>Click &ldquo;OK&rdquo; to the prompt.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-UploadDone.png" alt="" /></li>
<li>Save your workbook.</li>
<li>Repeat Steps 2-11 for each additional report you wish to import.</li>
<li>Next Select the &ldquo;Vuln Trending&rdquo; tab.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-VulnTab.png" alt="" /></li>
<li>In the top left, click the &ldquo;Refresh Vulnerabilities&rdquo; button. <em>NOTE: you need to complete a refresh any time you import data into this worksheet, this will update the table below.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-VulnRefresh.png" alt="" /></em></li>
<li>Click on the &ldquo;Charts&rdquo; tab.</li>
</ol>
</ol>
<p><img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-Chart.png" alt="" /></p>
<ol>
<li>Update the &lt;ACCOUNT&gt; text at the top of the sheet with your account name.&nbsp; <em>*OPTIONAL* - while the remaining steps are optional it is recommended that you complete them for this will help increase your visibility and will help you to better prioritize your remediation efforts.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-Dashboard.png" alt="" /></em></li>
<li>Click the Asset Overview tab.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-AssetOverview.png" alt="" /></li>
<li>The two columns that must be completed in this worksheet are &ldquo;IP/Hostname&rdquo; &amp; &ldquo;Device Criticality&rdquo; and determining both of these items is a manual process. To gather a list of all IP/Hostnames (these are the devices Nessus identified within your monthly scan) you need to go to each month tab for which you did a data import then highlight &amp; COPY all entries within column &ldquo;A&rdquo; and paste into a new excel document.&nbsp; NOTE: Keep all data within ONE Column.</li>
<li>Next, you&rsquo;ll need to remove all duplicates.&nbsp; Within the next Excel document highlight the column where you pasted your data into. In the Excel Ribbon bar click the &ldquo;DATA&rdquo; tab then select &ldquo;Remove Duplicates&rdquo;.&nbsp;<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-AssetDup.png" alt="" /></li>
<li>Click OK to the default prompt.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-DupsPrompt.png" alt="" /></li>
<li>Click OK to the Excel notice.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-DupOK.png" alt="" /></li>
<li>Now highlight all of the unique values identified, select COPY, then PASTE into Cell &ldquo;A4&rdquo; of your Asset Overview tab. Once complete you&rsquo;ll need to work on labeling the Device Criticality (Column C) for each asset.<img src="https://github.com/njfanelli/Nessus-Metrics/blob/master/Image-AssetCopy.png" alt="" /></li>
<li>Once complete press &ldquo;F9&rdquo; on your workbook to manually force any calculations to update.</li>
<li>Finally save your workbook.</li>
</ol>
<p>That&rsquo;s all!! Your data has now been imported into the tool and you should now begin to see some trending data within your GREY worksheets within the tool.</p>
<p><u>Helpful Hints:</u></p>
<ul>
<li>DO NOT rename the tabs within the workbook.</li>
<li>When saving your document and/or recalculating the workbook BE PATIENT, depending on the amount of data it may take EXCEL time to run through (several mins even) at the bottom of the Excel application there is green bar that provides the status of the save or update request.</li>
</ul>
