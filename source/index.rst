Aspose.OMR for .NET
==================================
It's easy to take words on your computer screen for granted and place them on a paper sheet: just click on the print button and you have  documents a few moments later.

Scanners aren't that difficult to use but many of them are simply taking a picture of the document and saving it on to your computer with dust particles  and you can't edit a copy of your file because the scanner won't recognize each individual character, but there are a number of devices that make optical character recognition(OCR) possible where each character on a page is scanned individually, so your papers are uploaded as actual text documents instead of pictures.

But how does that work?
------------------
 
The whole concept of translating text into electronic signal is very vast and there have been lots of different OCR approaches  over the past years. One of the earliest OCR tool was the `optophone <https://en.wikipedia.org/wiki/Optophone>`_  invented in 1914. The optophone was a device, used by the blind people, that scanned text and generated time-varying chords of tones to identify letters. It was one of the earliest known applications of sonification.
 

 
But it wasn't until the 1970s that OCR began to take a more familiar form for us with postal services using OCR to read addresses.

Here are the steps that make OCR work:

1.To cut out useless elements, so that the program can concentrate only on the  text .

2.To transform any colors or shades of gray in the image to black and white to make the words  easier to recognize.

3. To figure out which characters are on the page and compare each scanned letter pixel by pixel to a known trained before  dataset of fonts and decide which is the exact letter is on the page.
Each character is disassembled into curves and corners. Here OCR software can also make use of a dictionary so it won't accidentally miss out incorrect words.

.. image:: https://i.ibb.co/vh80fcQ/Diagram.jpg

However OCR itself obviously is not perfect, but with the help of **Aspose.OMR for .NET** from Aspose things get better.



`Aspose.com <https://about.aspose.com/>`_ is the market leader offering `20+ file format APIs <https://products.aspose.com/>`_  for different platforms including .NET, Java, C++ and Android, reporting solutions for Microsoft SharePoint and rendering extensions for Microsoft SQL Server Reporting Services and JasperReports with over `21,000 customers <https://websites.aspose.com/>`_  (including 80% of Fortune 100 companies) in 135 countries.

One of the instruments that eased the OMR process  is Aspose.OMR for .NET.
Here is a quick rundown through the technology.   

Aspose.OMR for .NET is a simple and practical `OMR <https://www.gdpicture.com/guides/gdpicture/Optical%20Mark%20Recognition.html>`_   tool for creating and recognizing MCQ(Multiple Choice Questions) papers, scans and photos - all types of forms, fonts and colors. 
Demo  materials with `code samples <https://github.com/aspose-omr/Aspose.OMR-for-.NET>`_ , demonstration templates and `videos             <https://products.aspose.app/omr/family>`_  can be launched out of the box to show software capabilities.

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube.com/embed/Uv7R7lzkXak" frameborder="0" allowfullscreen></iframe>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/f_EnXBVf-X0" frameborder="0" allowfullscreen></iframe>
    

Education
------------------
It is perfect omr software for teachers since minimum programming skills are required to create and recognize omr forms for test sheets, exams or assessments or more complex papers with IDs.

.. image:: https://products.aspose.com/omr/net/AnswerSheet.png 
.. image:: https://products.aspose.com/omr/net/OmrTest.png

Surveys
------------------
You can conduct any kind of surveys with Aspose.OMR: customer satisfaction surveys, evaluation surveys, public opinions, etc.


.. image:: https://products.aspose.com/omr/net/OmrSurvey.png 
 
Create your own template 
------------------

Aspose.OMR for .NET API provides methods to create OMR `templates <https://products.aspose.com/omr/net/>`_ from text description. Using this feature developers can create highly customizable omr sheets ready for print. API supports several types of elements, including text, choice box (question), answer sheet (several columns of questions), grid (complex values that consist of similar sections). Generated images can be saved as ready-to-print PDF files or PNG images.
::

 // initialize engine and get template processor providing path to the .omr file
 OmrEngine engine = new OmrEngine();
 TemplateProcessor templateProcessor = engine.GetTemplateProcessor(templatePath);

 // path to the filled omr form image
 string imagePath = "MyTest1Photo1.jpg";

 // call recognition method and get the result
 RecognitionResult result = templateProcessor.RecognizeImage(imagePath);

 // path to the results file
 string exportPath = "Photo1Results.csv";

 // export results as csv string
 File.WriteAllText(exportPath, result.GetCsv());

     

Recognize OMR sheets
------------------

Aspose.OMR for .NET main feature is a recognition. API can recognize photos and scans in multiple image formats:JPEG, PNG, GIF, TIFF. In order to recognize images OMR engine requires .omr file, which is a template that describes position and content of the form. Generation provides template with each created form and we offer GUI application for creating template from any user image.
Recognition process is fast and accurate and takes just a couple of seconds per image, depending on the image quality and size.The recognition results can be saved as JSON or CSV files

::

 // path to the .omr file
 string templatePath = "MyTest1.omr";
 // initialize engine and get template processor providing path to the .omr file
 OmrEngine engine = new OmrEngine();
 TemplateProcessor templateProcessor = engine.GetTemplateProcessor(templatePath);
 // path to the filled omr form image
 string imagePath = "MyTest1Photo1.jpg";
 // call recognition method and get the result
 RecognitionResult result = templateProcessor.RecognizeImage(imagePath);
 // path to the results file
 string exportPath = "Photo1Results.csv";
 // export results as csv string
 File.WriteAllText(exportPath, result.GetCsv()); 
             
To sum up everything that is written above  with Aspose.OMR for .NET  there is no need to spend hours reading the documentation or trying to figure out the code.This simple yet functional instrument can be used in different scenarios.

**Getting started guides**

 * https://docs.aspose.com/omr/net/system-requirements/ 
 * https://docs.aspose.com/omr/net/installation/
 * https://docs.aspose.com/omr/net/how-to-run-the-examples/

**Our blog here** 
 * https://blog.aspose.app/

**Purchase**  
 * sales@aspose.com 

**In case of any questions please don`t hesitate to contact us**                  
 * https://forum.aspose.com/ 

**You can always find more in the implementation of the above along in our regularly updated documents** 
 * https://docs.aspose.com/
