# windows

[Environment]::SetEnvironmentVariable("Path", $env:Path + ";C:\tools", "Machine")

choco install sysinternals --params "/InstallDir:C:\tools" -y --force

choco install notepadplusplus -y --force

choco install nirlauncher -y --force

choco install wireshark -y --force

choco install firefox -y --force
