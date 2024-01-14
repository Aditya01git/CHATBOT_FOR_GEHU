

  ###  The INSTRUCTIONS FOR RUNNING THE CHATBOT  ###


    1. Note that python compiler version should be greater than  3.8 and lower than the version 3.11
        {As pytorch don't support 3.12 in this current time}.

    2. From command prompt  you have to install pytorch for making the chatbot (Neural Network).{Data size maybe around 2.7GB}

    3. Command in command prompt can be obtain by going to the official website of pytorch.org.

    4. Some libraries and package you may also need to install :
        I. nltk
        II. numpy
        III. nltk 'punkt' package
        IV. tkinter
    
    5. First at all you need to run train.py to make 'data.pth' which will be used for created by the NLP processing and be saved in 'data.pth'

    6. Here, GUI is created with the help of tkinter library ussed in python (which is in app.py)

    7. Functions of files:
        1. app.py - Gives chatbot GUI with help of 'tkinter' and 'chat.py'.
        2. chat.py - It use 'data.pth' and model.py to make a response .
        3. model.py - It's Brain of Chatbot(Neural Net).
        4. nltk_use.py - Here NLP of chatbot done using nltk library.
        5. train.py - Here Processed Data from Json is put in a file 'data.pth'  with the help of 'nltk_use.py' .
        6. Json(for Gehu).json -Data for the chatbot.

    8.  Note - We can run the code in terminal by running the file 'chat.py'.
             - Here in the repository 'data.pth' is not there you can make by running 'train.py'.
             - Also there will be cache file after running the code.


    THANK YOU
