
Aspose.OMR for .NET
==================================

`Aspose.com <https://about.aspose.com/>`_ is the market leader offering `20+ file format APIs <https://products.aspose.com/>`_  for different platforms including .NET, Java, C++ and Android, reporting solutions for Microsoft SharePoint and rendering extensions for Microsoft SQL Server Reporting Services and JasperReports with over `21,000 customers <https://websites.aspose.com/>`_  (including 80% of Fortune 100 companies) in 135 countries.

One of the instruments that eased the OMR process  is **Aspose.OMR for .NET.**
Here is a quick rundown through the technology.   

Aspose.OMR for .NET is a simple and practical `OMR <https://www.gdpicture.com/guides/gdpicture/Optical%20Mark%20Recognition.html>`_   software for creating and recognizing MCQ(Multiple Choice Questions) papers, scans and photos - all types of forms, fonts and colors. 
Demo  materials that include `code samples <https://github.com/aspose-omr/Aspose.OMR-for-.NET>`_ , demonstration templates and `videos             <https://products.aspose.app/omr/family>`_  can be launched out of the box to showcase software capabilities and workflow.

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube.com/embed/Uv7R7lzkXak" frameborder="0" allowfullscreen></iframe>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/f_EnXBVf-X0" frameborder="0" allowfullscreen></iframe>
    

Education
------------------
It is perfect omr software for teachers since minimum programming skills are required to create and recognize omr forms.Simple sheets for test, exams or assessments or more complex papers with IDs, text questions and multiple choice questions, Aspose.OMR for .NET can handle it all. 

.. image:: https://products.aspose.com/omr/net/AnswerSheet.png 
.. image:: https://products.aspose.com/omr/net/OmrTest.png

Surveys
------------------
Conduct surveys of any kind using Aspose.OMR: customer satisfaction surveys, evaluation surveys, public opinions, etc.


.. image:: https://products.aspose.com/omr/net/OmrSurvey.png 
 
Create your own template 
------------------

Aspose.OMR for .NET API provides methods to generate OMR `templates <https://products.aspose.com/omr/net/>`_ from text description. Using this feature developers can create highly customizable nice looking omr sheets ready for print. API supports several types of elements, including text, choice box (question), answer sheet (several columns of questions), grid (complex values that consist of similar sections). Generated images can be saved as ready-to-print PDF files or PNG images.
No need to start from empty list! Take a look at demonstration markups and generated images for a good understanding of generation capabilities and things you can start on. 



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

Aspose.OMR for .NET main feature is a recognition. API can recognize photos and scans in multiple image formats, including JPEG, PNG, GIF, TIFF, BMP. In order to recognize images OMR engine requires .omr file, which is a template that describes position and content of the form. Generation provides template with each created form and we offer GUI application for creating template from any user image.
Recognition process is fast and accurate and takes just a couple of seconds per image, depending on the image quality and size. This allows processing large numbers of forms in short amount of time.
The recognition results can be saved as JSON or CSV files

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
             
Easy to use
------------------

Aspose.OMR offers an intuitive API with obvious methods signatures. There is no need to spend hours reading the documentation or trying to figure out the code. Simple yet functional, API can be used in different scenarios.

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
