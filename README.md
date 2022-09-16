# SMART Health Links Designs

This work provides SMART Health Links (https://docs.smarthealthit.org/smart-health-links/) and implementers with (1) guidance on appropriate display and use of SMART Health Links and (2) reference designs. 

The overall objective is to encourage consistent visual representations of SMART Health Links to increase recognition among users. Use of reference designs is not a requirement, but we certainly encourage it where appropriate.

Note that SMART Health Links are under active development. These guidelines and designs will change as needed to reflect updates to the spec as they are made. 

## Designs

The following designs are available as PNG and PSD files. More formats will follow. 

| File | Description |
|-----------|---------|
| [SMART Health Link Setup](Generic_Mobile_UX_Link_Set-up.png) | Setup screen for a particular SMART Health Link, allowing the user to view or configure expiration and passcode and to activate the link  |
| [SMART Health Link Management](Generic_Mobile_UX_Link_Manage.png) | Sharing and management screen for a particular SMART Health Link, allowing the user to view, copy, and share the link as well as view and manage access |
| [SMART Health Link QR](Generic_Mobile_UX_SHL_QR.png) | QR code display screen for a particular SMART Health Link |
| [SMART Health Link Access Log](Generic_Mobile_UX_Access_Log.png) | Access log screen for a particular SMART Health Link |

## Key UX Elements

### SMART Health Link Setup
Provide users with a clear overview of the SMART Health Link they plan to create (depicted in [SMART Health Link Setup](Generic_Mobile_UX_Link_Set-up.png)). Include,

* Label for the link (e.g. “Jane’s Complete Immunizations”)
* Expiration information
* Passcode
* Description or list of data included in the SMART Health Link, or the action the link initiates, if not otherwise obvious in the label or UX

Be sure that users understand that by activating this link, all of the referenced data will be available to anyone with access to the link.

### SMART Health Link Management
For active SMART Health Links, provide users with tools to manage the key details of that link (depicted in [SMART Health Link Management](Generic_Mobile_UX_Link_Manage.png)). Users should be able to view or configure,

* The Label for the link (e.g. “Jane’s Complete Immunizations”)
* Expiration date
* Passcode
* The link URI

Users should also have the ability to

* View the access log for the link
* Deactivate the link

### SMART Health Link Sharing
For active SMART Health Links, provide users with tools to share that link as they see fit (depicted in [SMART Health Link Management](Generic_Mobile_UX_Link_Manage.png)).

Provide users with the link URI for sharing, and make it as easy as possible to copy the link to minimize errors. This could include automating copying the URI to their clipboard or sending the URI to operating system's built-in share functionality.

Make it clear to users whether or not the shared link will open a web viewer for the recipient or if the link needs to be opened by an application that understands SMART Health Links.

Be sure that users understand that by sharing this link, all of the referenced data will be available to anyone with access to the link.

### SMART Health Link QR Code
For active SMART Health Links, provide users with tools to share as a QR code as they see fit (depicted in [SMART Health Link QR](Generic_Mobile_UX_SHL_QR.png)).

QR codes should be presented in close proximity to the Label for the SMART Health Link so it is clear what is being shared. Include any other key information needed to identify the link and understand the contents, such as patient name or date of birth.

QR Codes should be rendered in black on a white background only to maximize contrast. The QR code should have a clear white border.

Embed the SMART logo in the QR code to increase recognition by users and verifiers.

Be sure that users understand that by sharing this QR code, all of the referenced data will be available to anyone with access to the link.

### SMART Health Link Access Log
Provide users with a list of organizations or people who have accessed a particular link.

For each access log record, display 

* The label for the link, especially if displaying logs for multiple links
* The recipient, which is the organization or person’s name provided when the link was accessed
* The date(s) the link was accessed

Be sure users understand that the recipient name is provided by the recipient and may not be verified.

### Displaying Patient and Clinical Data
All patient data and clinical data that are referenced by the SMART Health Link should be displayed clearly, prominently, and with clear labels, as they are in the corresponding data payload.

If data must be reformatted, adjusted for legibility, or translated, make every effort to ensure that they are consistent with the original data payload.

### Additional Information
Provide key information about SMART Health Links, including that they 

* Provide access to important health information
* Can be scanned or shared to verify the information with the issuer

Provide a privacy reminder that scanning the QR code or sharing the link will transmit all of the referenced personal and clinical data.

Note that these records can be used with apps, services, and locations where SMART Health Links are accepted.

Provide plain language explanations for data or concepts that might be difficult to understand.

Where possible, provide this information in the document or the same view as the SMART Health Link. For mobile applications and other cases where space is constrained, provide a means to link out to or pop up more information.

## License
These designs are made available under the [CC BY 4.0 license](https://creativecommons.org/licenses/by/4.0/). 

## Use of logos
The use of the SMART logo requires adherence to the SMART brand guidelines, which can be attested to at the SMART Health IT brand page, here: https://smarthealthit.org/smart-logo-for-smart-health-cards/

## Participants
Several groups, organizations, and individuals are contributing to SMART Health Links. Many of those are moving the work forward through work with [VCI](https://vci.org/) and [the Argonaut Project](https://confluence.hl7.org/display/AP/Argonaut+Project+Home).
