Filename: readme.txt

INSTALLATION INSTRUCTIONS
=========================

To make full use of the files provided on the CD-ROM, two software
applications need to be installed on your computer: Adobe's Acrobat
Reader and Wolfram Research's Mathematica. Acrobat Reader is used to
view and print the PDF (Portable Document Format) files on the CD-ROM.
The PDF files contain typeset text reproducing all the material in the
book Exploring Analytic Geometry with Mathematica. Mathematica is used
to view the notebook files and execute Descarta2D packages. If
Mathematica is not available, Wolfram Research's MathReader application
may be used to view the notebook files, although the Descarta2D packages
cannot be interactively executed using MathReader. 

Installing Acrobat Reader and Viewing PDF Files
-----------------------------------------------

Acrobat Reader is a licensed product of Adobe Systems Incorporated. It
is available as a free download from Adobe's web site, www.adobe.com.
For Windows systems, a version of Acrobat Reader is provided on the
CD-ROM and may be installed by double-clicking the 'ar302.exe' file icon
in the 'AcrobatReader' folder. For other computer systems, you should
download the appropriate files from Adobe's web site and follow the
installation instructions provided. Acrobat Reader may already be
installed on your computer system since PDF files are commonly used as a
format for typeset files downloaded from the World Wide Web. 

The entire typeset text of this book is stored on the CD-ROM in the
'Book' folder. Double-clicking any PDF file in the 'Book' folder will
cause Acrobat Reader to open the file and will allow viewing or printing
of the typeset text and illustrations. The PDF files can be read
directly off the CD-ROM using Acrobat Reader, or they can be copied to
any convenient location on your computer's hard disk drive. 

Installing Mathematica and Viewing Notebook Files
-------------------------------------------------

This book is designed around Mathematica, a product developed and
licensed by Wolfram Research Incorporated. To gain maximum benefit from
the book and the files provided on the CD-ROM, Mathematica should be
installed on your computer. Information about licensing Mathematica is
available at Wolfram's web site, www.wolfram.com. Instructions for
installing Mathematica are provided with Mathematica itself. Mathematica
should be installed before installing the Descarta2D files provided on
the CD-ROM. 

If Mathematica is not installed on your computer system, you can still
view the contents of the notebook files on the CD-ROM using Wolfram's
MathReader application (notebook files have the extension *.nb).
MathReader is also a licensed product of Wolfram Research Incorporated.
It is available as a free download from Wolfram's web site,
www.wolfram.com. For Windows systems, a version of MathReader is
provided on the CD-ROM and may be installed by double-clicking the
'Setupex.exe' file icon in the MathReader folder on the CD-ROM. If
Mathematica is installed on your computer system, do not install the
MathReader software. Mathematica provides all the capabilities of
MathReader. 

By using Mathematica or MathReader you can view any notebook file
directly off the CD-ROM. However, it is recommended that you install the
files in the folder 'Descarta2D' as described in the next section prior to
viewing them. Generally, you will not be able to follow the hyperlinks
in the notebook files unless they are installed on your computer's hard
disk drive as described in the next section. 

Installing the Descarta2D Files
-------------------------------

When Mathematica or MathReader is installed on your computer system, a
directory structure is created providing a standard location for
installing applications such as Descarta2D. On a Windows system the
standard Mathematica installation creates a directory structure whose
path name is 

c:\Program Files\Wolfram Research\Mathematica\3.0\AddOns\Applications\

Mathematica and MathReader will search this directory when trying to
locate packages (*.m files) and notebook files (*.nb files). In order to
install Descarta2D and related documentation so that Mathematica can
find these files, copy the 'Descarta2D' folder and all its contents from
the CD-ROM into the Applications folder of the directory path named
above. 

If you plan to use Descarta2D on a different operating system, refer
to the installation instructions for your Mathematica system to
determine the name of the proper directory path for add-on applications.
This information is also provided in Wolfram's Mathematica book. For
example, the high-level directory name for Mathematica on a Macintosh is
Mathematica 3.0. On a Unix or NeXT system the high-level directory name
/usr/local/Mathematica3.0.

Mathematica Help Browser
------------------------

The interactive Front End program that serves as the user interface for
Mathematica provides a Help Browser for accessing Mathematica
documentation (in fact, the entire text of Stephen Wolfram's Mathematica
book can be accessed using the Help Browser). The Help Browser is
activated by clicking the 'Help>Help...' item on the Front End's menu
bar. The Descarta2D documentation and this entire book can also be linked
into the Mathematica Help Browser. This is accomplished by clicking the
'Help>Rebuild Help Index...' item on the Front End's menu bar after the
Descarta2D folder has been copied into the proper folder. After the help
index is rebuilt, the Descarta2D documentation and the notebooks
representing this book can be accessed by clicking the 'Add-ons' radio
button on the Help Browser dialog. The high-level category name that
opens access to the Descarta2D categories is 'Descarta2D'.

Package Loading
---------------

In order to initialize the Descarta2D software in any Mathematica session
enter the command <<Descarta2D`. This command will load the
initialization file for Descarta2D and will enable Mathematica to find
and load any other Descarta2D package as it is needed.
