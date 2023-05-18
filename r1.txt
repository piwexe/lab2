echo off
set /p dummy = press F
md Boico
cd Boico
md Artiom
cd Artiom
md Mihailovich
set /p dummy = press F
cd C:\lr2\lr22
cd Boico
echo > 01062002.txt
cd Artiom
cd Mihailovich
echo > NOTEBOOK.txt
set /p dummy = press to del files
cd C:\lr2\lr22
del Boico /S /Q /F
set /p dummy = press to del
cd Boico
cd Artiom
rd Mihailovich
cd ..
rd Artiom
cd ..
rd Boico
pause