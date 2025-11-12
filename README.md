Ce dépôt documente l'analyse complète d'un exécutable Windows (dismember.exe) généré par PyInstaller, dont le but est de révéler un mécanisme de chiffrement complexe (XOR) et de trouver la clé finale pour "ouvrir un portail" (Magic The Gathering Challenge).


Outil utilisé:

Ghidra / IDA Pro,"Désassemblage, Décompilation (Hex-Rays), et analyse du bootloader x64 et de la shellcode brute."
HxD Editor,"Inspection hexadécimale, détermination des offsets PE, et patching du Magic Number pour l'extraction."
Detect It Easy (DIE),Identification de la signature PyInstaller et des limites de l'Overlay.
pyinstxtractor,Outil d'extraction de l'archive Python PKG (utilisé après patching).
pycdc : extraction du code python depuis PYC
