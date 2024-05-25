# Enable NIST800-53 on Microsoft Defender for Cloud

<h2>Purpose</h2>

- Enable NIST800-53 regulatory compliance on Microsoft Defender for Cloud.

NOTE: Enabling NIST800-53 and allowing the rules to import will take around 12 hours to complete.
#

<h3>Enabling NIST800-53</h3>

<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/enable-nist80053-images/main/1.png"/>

Go to Microsoft Defender for Cloud and enter the "Regulatory compliance" blade. Select "Manage compliance standards".

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/enable-nist80053-images/main/2.png"/>

Select the respective Azure Subscription you want to enable the compliance standards for.

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/enable-nist80053-images/main/3.png"/>

Under "Security Policies" enable "NIST SP 800-53 Rev. 5".

#
<img src="https://raw.githubusercontent.com/melisaaaaaaaaa-er/enable-nist80053-images/main/4.png"/>

Make sure to disable "Microsoft cloud security benchmark" or else NIST800-53 will not show up in the Regulatory Compliance blade of Microsoft Defender for Cloud.
