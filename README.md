# What is the COM !! > Component Object Model
The Microsoft Component Object Model (COM) is a platform-independent, distributed, object-oriented system for creating binary software components that can interact. COM is the foundation technology for Microsoft's OLE (compound documents), ActiveX (Internet-enabled components), as well as others.,

[Learn more on >_ Component Object Model (COM)](https://msdn.microsoft.com/en-us/library/windows/desktop/ms694363%28v=vs.85%29.aspx)
====================================================================================||>
====================================================================================||>
# what is Authors Bypass UAc Thanks On friends
[@enigma0x3](https://twitter.com/enigma0x3)

[@FuzzySec](https://twitter.com/FuzzySec)
-----
[@OJ](https://twitter.com/TheColonial)

# What is the Script Bypass !
      This module will bypass Windows UAC by creating COM handler registry entries in the
        HKCU hive. When certain high integrity processes are loaded, these registry entries
        are referenced resulting in the process loading user-controlled DLLs. These DLLs
        contain the payloads that result in elevated sessions. Registry key modifications
        are cleaned up after payload invocation.
        This module requires the architecture of the payload to match the OS, but the
        current low-privilege Meterpreter session architecture can be different. If
        specifying EXE::Custom your DLL should call ExitProcess() after starting your
        payload in a separate process.
        This module invokes the target binary via cmd.exe on the target. Therefore if
        cmd.exe access is restricted, this module will not run correctly
        ,,
====================================================================================||>
====================================================================================||>
