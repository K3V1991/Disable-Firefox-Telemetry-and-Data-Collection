<p align="center"><img src="https://github.com/K3V1991/Disable-Firefox-Telemetry-and-Data-Collection/blob/main/Data-Collection.png" width="200"></a>
<h1 align="center"><b>How to disable Firefox Telemetry and Data Collection</b></h1>
<br />

<p align="center">
<a href="https://ko-fi.com/k3v1991" alt="Ko-fi"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white"> &emsp;
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="PayPal"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white"> &emsp;
<a href="https://github.com/K3V1991/Donate-Crypto/blob/main/README.md" alt="Crypto"><img src="https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white">
</p>
<hr />
<br />

## NFO:
Mozilla has provided few Settings on Options Page to select what kind of Data do you want to share with Mozilla and want to send to Mozilla Servers. <br />
You can turn on/off Options such as "Allow Firefox to send technical and interaction data to Mozilla", "Allow Firefox to install and run studies" and "Allow Firefox to send Crash Reports to Mozilla" Servers. <br />
You can change these settings using "Privacy & Security" Section. <br />
Even after you disable these Options, Firefox still collects and sends Data to Servers. 
<br />
<br />

## Disable Telemetry and Data Collection:
1. Open Firefox and type ```about:config``` in the Addressbar and press Enter. It'll show you a Warning Message, click on "Accept the Risk and Continue" Button
2. In the Search Bar, type each of the following Preferences and then set them to the Value provided to the right:
<br />
<br />

Preference | Value to change |
| --- | --- |
| browser.newtabpage.activity-stream.feeds.telemetry | false |
| browser.newtabpage.activity-stream.telemetry | false |
| browser.ping-centre.telemetry | false |
| datareporting.healthreport.service.enabled | false |
| datareporting.healthreport.uploadEnabled | false |
| datareporting.policy.dataSubmissionEnabled | false |
| datareporting.sessions.current.clean | true
| devtools.onboarding.telemetry.logged | false |
| toolkit.telemetry.archive.enabled | false |
| toolkit.telemetry.bhrPing.enabled | false |
| toolkit.telemetry.enabled | false |
| toolkit.telemetry.firstShutdownPing.enabled | false |
| toolkit.telemetry.hybridContent.enabled | false |
| toolkit.telemetry.newProfilePing.enabled | false |
| toolkit.telemetry.prompted | Number Value 2 |
| toolkit.telemetry.rejected | true
| toolkit.telemetry.reportingpolicy.firstRun | false |
| toolkit.telemetry.server | Delete URL |
| toolkit.telemetry.shutdownPingSender.enabled | false |
| toolkit.telemetry.unified | false |
| toolkit.telemetry.unifiedIsOptIn | false |
| toolkit.telemetry.updatePing.enabled | false |
