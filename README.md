# apache-tomcat-patches
Collection of patches for apache-tomcat.

## 57665 support x-forwarded-host
Patch from here: https://bz.apache.org/bugzilla/show_bug.cgi?id=57665#c13

Allow x-forwarded-host header to be evaluated by RemoteIpValve and RemoteIpFilter.

Original patch was applied against tomcat version 8.0.46, 8.5.21, sources were cleaned up and then the patches files were re-created.
