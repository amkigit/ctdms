# Installation #

## Setup ##

The package can be installed  by using the command

`python setup.py install`


This will create a cTDMS directory in /site-packages and copy the python scripts and the documentation to this directory.
After installation the NILIBDDC library from National Instruments has to be installed.



## Installation of the NILIBDDC library from National Instruments ##

<p>To use the cTDMS package the NILIBDDC library from National Instrumentshas to be installed.</p>

<p>This library can be downloaded from:</p>
<blockquote>
<div><a href='http://research.ni.com/run/2007codelicenseagree'><a href='http://research.ni.com/run/2007codelicenseagree'>http://research.ni.com/run/2007codelicenseagree</a></a></div></blockquote>

From there the file dominonilibddc.zip can be downloaded.
From this zip file following file should be copied to the cTDMS package directory:
```
\dev\bin\32-bit\nilibddc.dll
\dev\bin\32-bit\nilibddc.lib
\dev\bin\32-bit\uspTdms.dll
\dev\bin\32-bit\usiEx.dll
\dev\bin\32-bit\uds.dll
\dev\bin\32-bit\usiPluginTDM.dll
\dev\bin\32-bit\dacasr.dll
\dev\bin\32-bit\tdms_ebd.dll
\dev\bin\32-bit\stlport.5.0.dll
\dev\bin\32-bit\xerces-c_2_8_usi.dll
\dev\bin\32-bit\hdf5dll.dll</pre>
```

<p>and the <strong>whole</strong> directory</p>
`\dev\bin\32-bit\nilibddc.lib\DataModels`


<p>Copy the cTDMS package directory to your sitepackage path, e.g. <code>c:\Python26\Lib\sitepackage\cTDMS</code>.<br>
<br>
<p>At the end of the installation the cTDMS directory should contain following files:</p>
<pre><code>DATAModels<br>
html<br>
__init__.py<br>
cTDMS.py<br>
dacasr.dll<br>
hdf5dll.dll<br>
nilibddc.dll<br>
nilibddc.lib<br>
stlport.5.0.dll<br>
tdms_ebd.dll<br>
uds.dll<br>
usiEx.dll<br>
usiPluginTDM.dll<br>
uspTdms.dll<br>
xerces-c_2_8_usi.dll<br>
</code></pre>