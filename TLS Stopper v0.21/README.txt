----------Break on TLS callback for Immunity Dbg---------
v0.2
1. Install plugin
2. If plugin cannot set option "Make first pause at: System breakpoint" in "Events" and set
"Ignore CRC of code section" in "Security" automatically, set it manually
3. Restart debugger.
4. Load "tls.exe" and "tls_3.exe" [3 callbacks before entry point] 
(from example[test] directory) in to ImmunityDbg  
 
----------------------------------------------------------
(c) 0x0c0de 2008