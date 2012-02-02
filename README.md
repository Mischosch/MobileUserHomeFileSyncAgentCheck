## About

This small Apple Script checks ~/Library/Preferences/com.apple.FileSyncAgent.plist for the "havePHDSyncSet" attribute/record.
havePHDSyncSet must be set to true to enable Mobile User Home folder sync.

This scripts checks, if havePHDSyncSet value exists. 
If not, it is created and set to true.
If it is set to false, you can set it to true by using the Repare button.

This tool should only be used for Mobile Home folders that should be in sync with remote home folder and don't do their job like they should.
Perhaps it can help someone out there with same problems.

Read: http://sch0ll.de/blog/article/my-first-apple-support-experience for some background information about my syncing problems.
