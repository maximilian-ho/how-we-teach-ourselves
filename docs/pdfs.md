# Annotating pdf textbooks using Foxit PDF editor 

When learning from pdf textbooks, we type our notes directly onto the pages. This helps us to process the concepts one step at a time and remember the concepts when we review the textbooks later.   

**Downloading the textbooks**  
We download the pdf textbooks from LibGen.  

**Editing bookmarks using Visual Studio Code**  
To make the textbooks easy to navigate, they must have comprehensive bookmarks. Most textbooks from LibGen have bookmarks with unnecessary prefixes and too many levels. Hence, we export the bookmarks as an XML file and use Visual Studio Code to edit them using regular expressions. This is much faster than editing the bookmarks manually. 

![image](https://github.com/maximilian-ho/articles/assets/94465856/93a4727d-2fc2-4ee3-9341-ecb56b9919e4)

![image](https://github.com/maximilian-ho/articles/assets/94465856/3667ef53-9f8c-4be9-aa92-e2371cac850d)

The images below show the old bookmarks (left image) and the improved bookmarks (right image).   

![image](https://github.com/maximilian-ho/articles/assets/94465856/d14d8bb5-9d8e-4bdb-82f0-9c1243167a05)   

**Typing definitions**    
Whenever a new term is defined, we type our own definition and make the new term bold. 

![image](https://github.com/maximilian-ho/articles/assets/94465856/d207717d-583d-48ce-bc91-c0924e80299f)

![image](https://github.com/maximilian-ho/articles/assets/94465856/71b12ae3-6940-4db1-ac7b-e1b169719e54)

**Adding equations**  
Currently, we cannot type equations in Foxit pdf editor. Hence, we type our equations in Microsoft Word. After that, we use the Snipping Tool to copy an image of the equation, then paste the image onto the page.

![image](https://github.com/maximilian-ho/articles/assets/94465856/64f7d36f-e23e-4f9b-b76d-3d8bcf741c23)

![image](https://github.com/maximilian-ho/articles/assets/94465856/2cd5c31d-2a0f-4e40-ad1e-d0b17cb8181e)

![image](https://github.com/maximilian-ho/articles/assets/94465856/a4fd5658-b101-4141-b8e5-fa3d4aaa0646)

**Making space**  
When there's no space on a page to add a note, we duplicate the page. We then delete the bottom half from the top page, and the top half from the bottom page. This creates plenty of empty space that we crop out after adding our notes.  

![image](https://github.com/maximilian-ho/articles/assets/94465856/23940f6c-44f0-491b-8369-66aa301fc9ec)

![image](https://github.com/maximilian-ho/articles/assets/94465856/864d8490-1936-4791-8b82-109e780a4102)

![image](https://github.com/maximilian-ho/articles/assets/94465856/bc7a14c2-4da6-4a76-9d10-ac285969d86a)   

**Speeding up slow save times**   
If Foxit PDF Editor is taking a long time to save files, we can speed it up by following these instructions ([link](https://kb.foxit.com/hc/en-us/articles/4413854556436-Disable-the-feature-of-optimizing-PDF-file-automatically-when-saving-PDF-file-in-Foxit-PDF-Editor)). 

