Icy - copyright 2019 - Institut Pasteur
An open community platform for bio image analysis - http://icy.bioimageanalysis.org

Icy has been created by the Bio Image Analysis team at Institut Pasteur - https://research.pasteur.fr/fr/team/bioimage-analysis
Icy is free and open source, it has been funded both by Institut Pasteur and the FBI consortium - https://france-bioimaging.org

Source code is provided in the main application package (in the icy.jar archive file) but can also be found on the GitHub repository - https://github.com/Icy-imaging/Icy-Kernel


Note for OSX users
------------------
First, you need to have java installed on your system. Sometime java is installed but just for web applications (JRE) in which case you need to install the JDK 8 for Mac OSX.
We strongly recommend to keep JDK 8 which is more stable than newer version of Java (9 or above) so if possible try to keep Java 8 as the default version.
Then ensure you have authorized the application in the security preferences as OSX won't allow external application by default:

* OSX 10.11 or older
  You can resolve the problem by going to:
  System --> Preferences --> Security --> Privacy then change Allow applications downloaded from to Anywhere
  Or you can select to authorize Icy application specifically.

* OSX 10.12 or above
  You don't have anymore the Anywhere choice here and because of system's restrictive security rules you may not be able to launch Icy properly even by forcing it.
  In this case you need to execute the osx-appfix file (located in the Icy folder) by right clicking on it (or Ctrl + click) and use Open.
  You should now be able to use Icy normally.

* OSX 10.12 or above - alternate method
  If the previous method didn't worked (sometime the script do not execute properly), you can try to execute the osx-appfix command manually:
  - Open the Terminal app
  - Go into the folder of Icy (using cd command)
  - Execute the following command: xattr -dr com.apple.quarantine icy.app
  Then hopefully now you should be able to execute Icy normally :)


Contributors
------------

Kernel architecture and code
    Stephane Dallongeville and Fabrice de Chaumont

Website graphic design
    Marcio de Moraes Marim

Website code
    Fabrice de Chaumont

EzPlug and Protocols
    Alexandre Dufour

Scripting
    Thomas Provoost, Timoth�e Lecomte and Stephane Dallongeville

MicroManager for Icy
    Thomas Provoost, Irsath Nguyen and Stephane Dallongeville

Head of unit
    Jean-Christophe Olivo-Marin

Many thanks to beta testers and contributors
    Nicolas Chenouard
    Alexandre Dufour
    Nicolas Herv�
    Vannary Meas-Yedid
    Sorin Pop
    Thibault Lagache
    Biomedical Imaging Group - http://bigwww.epfl.ch/
    M. Geissbuehler and T. Lasser - http://www.opticsinfobase.org/oe/abstract.cfm?URI=oe-21-8-9862
        "How to display data by color schemes compatible with red-green color perception deficiencies" Opt. Express 21, 9862-9874 (2013)        

Libraries used in Icy
    Bio-Formats - http://www.openmicroscopy.org/site/products/bio-formats
    VTK - http://www.vtk.org/
    Substance / Insubstancial - https://github.com/Insubstantial/insubstantial
    Flanagan - http://www.ee.ucl.ac.uk/~mflanaga/java/
    Jama - http://math.nist.gov/javanumerics/jama/
    JFreeChart - http://www.jfree.org/jfreechart/
    JTransforms - https://sites.google.com/site/piotrwendykier/software/jtransforms
    Xuggler - http://www.xuggle.com/xuggler/

Libraries/tools integrated within the Icy website
    phpBB - TinyMCE

Development tool for profiling/debugging
    YourKit is kindly supporting open source projects with its full-featured Java Profiler.
    YourKit, LLC is the creator of innovative and intelligent tools for profiling Java and .NET applications.
    Take a look at YourKit's leading software products: YourKit Java Profiler and YourKit .NET Profiler. 