# EduSense
Problem that EduSense aim For:
Education for Blind People.

Solution I proposed:
As blind people are not able to read books notes ,They uses brails to study for Hard copy of books and Audio Description for PDF's. As audio description help them to access all the data available on internet ,but What about the books which are not available online and the individual wants to read a book available offline. And creating Brail System for a offline book which is quite infeasible as a lot of plates is required.
So EduSense Does that for offline books as well as the PDF's available by uploading PDF's to OCR API and the praised text will be in in the form of JAVA SCRIPT OBJECT NOTATION which will be called by the API key and will work as Audio Description using  Text-To-Speech ,And for reading live books,templates and Images,An individual just have to wear a camera and headphone which basically captures frames from live video and using Image Processing algorithm, A desired text is cropped and get uploaded to the OCR api which basically works bit by bit by extraction alphabets with checking the spacing between the lines.And gives an output as string which then converted into Audio.Due to while loop an Indiidual doesnt required extra space to save images for the books from live video,its get replaced by new one by pressing a key of particular ASCII value.
Technology Stack:
Image Processing, Python, OpenCV, Optical Character Recognition(OCR API)
Advantages:
1. Storage Efficient
2.Work for Both Images as well as PDF(As Audio Books work for only PDF's)
3.Cost Efficient as a Poduct 
