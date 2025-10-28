# **Purpose of Creo CaseAssist:** 
>Simplify data entry to Google Sheets and file transfer to outsourcing partners to reduce mistakes and decrease training time for new hires
## **Unchanged workflow steps:**
>Scan folders & Rxs are downloaded manually or by Evident

>Folders are named in \[Pan #]-\[Date]\_\[Dr Last]\_\[PT Last] format manually or by Evident

>Scans are checked for quality and to ensure they match the Rx

> Cases are entered into ABS manually or by Evident
## **New program functionality:**
>Program accepts folders

>Folders can be batch-added or added one-by-one via drag-and-drop or a windows dialog

>Each folder creates a line in the GUI for the technician to select how the case will be handled

>Case handling options will be radio buttons to the right of the line in the GUI:
> - (radio button) SDS In House
>	- Scans uploaded to OneDrive
>	- Scans moved to NYC Active new\_scandata\_folder folder (NOT copied)
>	- Line created on SDS In House Google Sheet
> - (radio button) SDS Lab
>	- Scans uploaded to OneDrive
>	- Scans moved to NYC Active new\_scandata\_folder folder (NOT copied)
>	- Line created on SDS Lab Google Sheet
> - (radio button) Evident
>	- Scans uploaded to Evident Portal
>	- Scans moved to NYC Active new\_scandata\_folder folder (NOT copied)
>	- Line created on Evident Google Sheet
> - (radio button) Inosys C\&B
>	- Scans uploaded to Google Drive
>	- Scans moved to NYC Active new\_scandata\_folder folder (NOT copied)
>	- Line created on Inosys Google Sheet
> - (radio button) Solidex
>	- Scans moved to HV Active SOLIDEX\_ND folder (NOT copied)
>	- Line created on Solidex Google Sheet
> - (radio button) 3D Print Only
>	- Scans uploaded to HV Active 3DPRINT folder
>	- Scans moved to NYC Active new\_scandata\_folder folder (NOT copied)
>	- Line created on 3D Print Google Sheet
> - (radio button) Evaluate only
>	- Scans moved to NYC Active new\_scandata\_folder folder (NOT copied)
>	- Line not created

> When folders are added to Creo CaseAssistant, they are expected to remain in the same directory until *Process Case(s)* is clicked

> Multithreaded processing of cases when *Process Case(s)* is clicked


# TODO
- Logic for Google Sheet line creation
- Logic for Google Sheet line copying
- Logic for Google Sheet daily sheets
- Logic for OneDrive daily directories
- Logic for Google Drive daily directories
- Logic for Evident Portal \[Maybe ask Evident for help with this automation?]
- Logic for HV Active
- Logic for new\_scandata\_folder
- Store all directories in pickle format on NYC server



