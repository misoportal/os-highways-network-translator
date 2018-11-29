# OS Highways Network Translator


Miso, the leading translator of OS data sets, have released a fully featured solution for the complex OS Highways Network data set to the OpenSource community. The community has delivered a huge amount of value to the GIS world, and miso wants to support this. 
This release will provide the GIS community with a fantastic opportunity to adopt this very powerful new OS dataset.

The OS Highways Network dataset is both very powerful and hugely complex.  The miso translator cools this complexity, making the dataset usable in an everyday form.  Specifically it processes the data:

<ul>
  <li>In a one-click operation</li>
  <li>Into Geopackage format, together with all the files required for styling in MapInfo Pro</li>
  <li>With a workspace including both an OS Highways and an NSG Streets window</li>
  <li>Suitable for loading into any spatial database system</li>
  <li>Spatially referenced using British National Grid (BNG).</li>
</ul>
The solution is built on the widely available FME technology and released as an FME workspace which can be run on FME Desktop Pro 2018.1 upwards.  FME was chosen as it is the best technology to deliver the “heavy lifting” required and is widely adopted in both the OpenSource and GIS communities. 

An example of the data created from the OS Highways Network Translator, along with the relevant documentation can be found at <a href="https://s3-eu-west-1.amazonaws.com/free.data/SampleData-OS_HighwaysNetwork_Translator.zip">SampleData-OS_HighwaysNetwork_Translator</a>

# Instructions

Either click "Clone or download" and and click "Download ZIP" or if you have git installed then from a command prompt type: 

<code>git clone https://github.com/misoportal/os-highways-network-translator.git</code>

Just run the <code>_OSHighwaysNetwork.fmw</code> workspace to complete the entire translation. This may take some time, but may simply be left running unattended.

When starting, choose your folders using the Translation Parameters. Ignore any warnings of 'failure' for  feature types not in your data set.

Other FME workspaces will be run in turn to complete the translation. All the workspaces to be run must be in the same folder as this one.

When the translation is complete, go to the output folder you specified and open the <code>_OSHighwaysNetwork.wor</code> workspace file in MapInfo Pro.
