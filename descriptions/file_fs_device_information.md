FILE\_FS\_DEVICE\_INFORMATION represents output buffer \
in a call to \
NtQueryVolumeInformationFile with \
FileFsDeviceInformation information class. Structure is \
avaiable in &lt;ntddk.h&gt; header file from \
Win2000 DDK. \
DeviceType Numeric device types are \
defined in &lt;ntddk.h&gt; as FILE\_DEVICE\_\* \
precompiler definitions. \
Characteristics Or\-ed bit mask of \
device characteristic. Can be one of: \
FILE\_REMOVABLE\_MEDIA \
FILE\_READ\_ONLY\_DEVICE \
FILE\_FLOPPY\_DISKETTE \
FILE\_WRITE\_ONCE\_MEDIA \
FILE\_REMOTE\_DEVICE \
FILE\_DEVICE\_IS\_MOUNTED \
FILE\_VIRTUAL\_VOLUME \
FILE\_AUTOGENERATED\_DEVICE\_NAME \
FILE\_DEVICE\_SECURE\_OPEN

Documented by: \
Tomasz Nowak \
Requirements:

Library: ntdll.lib

See also: \
FS\_INFORMATION\_CLASS \
NtQueryVolumeInformationFile