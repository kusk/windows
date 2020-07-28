# windows

[Environment]::SetEnvironmentVariable("Path", $env:Path + ";C:\tools", "Machine")

choco install sysinternals --params "/InstallDir:C:\tools" -y --force

choco install notepadplusplus -y --force

choco install nirlauncher -y --force

choco install wireshark -y --force

choco install firefox -y --force

choco install dnspy -y --force

choco install 7zip -y --force

choco install hxd -y --force

choco install ghidra -y --force
