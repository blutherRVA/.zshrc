Pen,

Currently experiencing multiple issues that I belive are all related.

1) I appear to have three different paths within my computer, which are included in the following files. I am unsure how to either edit Path 'a' and Path 'c' and even
really what the best practice for a path structure should be.
    a. Terminal Path: When I do 'echo $PATH' I get one path
    b. .zshrc Path: The Path I have created and exists in my .zshrc file does not match the Terminal Path
    c. Anaconda Path: When I do 'echo $PATH' in the terminal within my Anconda Navigator - Jupyter Lab environment, I get a Path that does not match either of first two paths. 
    
2) I downloaded MacTeX to be able export .ipybn files as PDF files from Jupyter Lab. I keep getting an error when I try ot export it which directs me to a page saying I need 
  to download MacTeX so clearly it needs to be put in that Anconda path but, as said in section 1, not sure how to do that.
  
3) To switch gears and export the .ipybn file to PDF I tried making a Jupyter Notebook in VS Code. Was able to successfully export the file to PDF, however, the Python 'Pandas'
   package I need to import to do any Python data analysis throws an error when run, saying it does no exist. Works completely fine in the Anconda Navigator - Jupyter Lab environment, and I am even running VS Code with Anaconda.Have also tried to reinstall Pandas with pip and conda in VS Code to no avail. 
   
I belive all of these are related to paths but have been spinning my wheels of what to do get these to work, and what the correct way of having hte structured so I don't keep 
running into these problems. Additionally, i know my computer is in fact using my .zshrc file and not my .bshrc file because whenver I open a terminal in any of the above 
environemnts it echos 'Hello World' as I have instructed in the .zshrc file. Feel free to direct me to some reading that would be useful.

Sincerely,
Confused and Exasperated 
    

