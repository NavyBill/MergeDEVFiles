This application allows two ROS development files (.DEV) to be merged into one, larger, development file. There are some caveats however.

1. Any Preferred Direction entries will not be used.
2. Any Gap Jumps will be reset to UnSet
3. Any User graphics will not be merged.

This is a WORKING (Debug) executable right now, and bugs are probably present. If you find one, please let me know. It is also filled with 'belt and suspenders' code to ease my debugging. Most of this will be cleaned up for the final version.

I can be reached at: iss_boss@sbcglobal.net

NOTE: The executable will produce a MergeLog.log file in the directory where the executable in installed. In do NOT overwrite it, so it could grow large after much use. It whould be checked and deleted if it gets too large.

Bill
