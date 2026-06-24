# substack-notes-explorer v1.1
Exports all Notes from your Substack account via API and creates an interactive infographic from the data.

Follow instructions inside [notes-explorer.html](https://zedcade.github.io/substack-notes-explorer/notes-explorer.html) to export your own notes and generate your dashboard and hero image in three simple steps.

v1.1
* added indexedDB support to store exports for immediate viewing, plus multi Substack support (dropdown from handle on top of the html to select what export to view if more than one is present in the indexedDB).
* json Export optimizations
* large account support (experimental, shoudl work for 10k+ Notes, untested)

Disclaimer: Bookmarklet is working with Substack API as of June 21st 2026. Future changes to API will require js updates.

Sample Hero PNG (simple version):
<img width="2400" height="3332" alt="alexanderipfelkofer_substack_notes_heroimg_2026-06-22_19-46" src="https://github.com/user-attachments/assets/693fc914-4d79-4dfa-8cb3-ec6b3c976b78" />
