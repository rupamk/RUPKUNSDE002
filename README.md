# Instructions

## Requirement: 
    virtualenv==15.1.0

## Instructions to set-up:
    git clone git@github.com:rupamk/RUPKUNSDE002.git
    cd RUPKUNSDE002
    pip install virtualenv
    virtualenv venv
    source venv/bin/activate
    pip install -r requirements.txt

## Running Sample:

    python TopQuotes/Quotes.py 

## Sample Output:

    >>(venv) Rupams-MacBook-Pro:RUPKUNSDE002 rupamkundu$ python TopQuotes/Quotes.py 
    -------------------------------------------------
    ---------Authentication to Goodreads.com---------
    -------------------------------------------------
    Please Enter your GoodReads.com email address:rupam2422@gmail.com
    
    Please Enter your GoodReads.com password:*******
    
    Authenticated!! You are now logged in!
    -------------------------------------------------------
    Check Mark_Twain_top_quotes.json in ./TopQuotes/Data/ 
    -------------------------------------------------------
    
    Top 10 Quotes of Mark Twain
    ********************************************************
    Quote 1:If you tell the truth, you don't have to remember anything
    
    ********************************************************
    Quote 2:Good friends, good books, and a sleepy conscience: this is the ideal life
    
    ********************************************************
    Quote 3:Whenever you find yourself on the side of the majority, it is time to reform (or pause and reflect)
    
    ********************************************************
    Quote 4:The man who does not read has no advantage over the man who cannot read
    
    ********************************************************
    Quote 5:Never put off till tomorrow what may be done day after tomorrow just as well
    
    ********************************************************
    Quote 6:′Classic′ - a book which people praise and don't read
    
    ********************************************************
    Quote 7:I have never let my schooling interfere with my education
    
    ********************************************************
    Quote 8:The fear of death follows from the fear of life. A man who lives fully is prepared to die at any time
    
    ********************************************************
    Quote 9:A lie can travel half way around the world while the truth is putting on its shoes
    
    ********************************************************
    Quote 10:Never tell the truth to people who are not worthy of it
    
    ********************************************************
    -------------------------------------------------------
    Check Mark_Twain_top_quotes.json in ./TopQuotes/Data/ 
    -------------------------------------------------------

## File Storage Format

### Data is stored as "json" format inside ./GetFbPost/Data/ . The data shown above is stored as "Top_expedia_Facebook_Post.json":

    Quotes By:Mark Twain    
    0    
    Content    "If you tell the truth, you don't have to remember anything"
    Author    "Mark Twain"
    1    
    Content    "Good friends, good books, and a sleepy conscience: this is the ideal life"
    Author    "Mark Twain"
    2    
    Content    "Whenever you find yourself on the side of the majority, it is time to reform (or pause and reflect)"
    Author    "Mark Twain"
    3    
    Content    "The man who does not read has no advantage over the man who cannot read"
    Author    "Mark Twain"
    4    
    Content    "Never put off till tomorrow what may be done day after tomorrow just as well"
    Author    "Mark Twain"
    5    
    Content    "′Classic′ - a book which people praise and don't read"
    Author    "Mark Twain"
    6    
    Content    "I have never let my schooling interfere with my education"
    Author    "Mark Twain"
    7    
    Content    "The fear of death follows from the fear of life. A man who lives fully is prepared to die at any time"
    Author    "Mark Twain"
    8    
    Content    "A lie can travel half way around the world while the truth is putting on its shoes"
    Author    "Mark Twain"
    9    
    Content    "Never tell the truth to people who are not worthy of it"
    Author    "Mark Twain"

## Run Unit Test:

    >>(venv) Rupams-MacBook-Pro:RUPKUNSDE002 rupamkundu$ python TopQuotes/Test_quotes.py
    -------------------------------------------------
    --------Unit Testing Framework: quotes.py--------
    -------------------------------------------------
    Please provide an author name properly.
    .Please provide a Link properly
    ..Empty email! please provide a proper email!
    .Empty password! please provide a proper password!
    .Name cannot contain Numbers! Enter proper author name !
    .Name cannot contain Numbers! Enter proper author name !
    .Number of quotes should be >=1
    .Num of Quotes should be an Integer Value
    .-------------------------------------------------------
    Check  in ./TopQuotes/Data/ 
    -------------------------------------------------------
    ..-------------------------------------------------------
    Check  in ./TopQuotes/Data/ 
    -------------------------------------------------------
    ..HTTPSConnectionPool(host='www.xxxxxxxxxxxs.com', port=443): Max retries exceeded with url: /quotes/search?&q=mark+twain&commit=Search (Caused by NewConnectionError('<urllib3.connection.VerifiedHTTPSConnection object at 0x105c78a50>: Failed to establish a new connection: [Errno 61] Connection refused',))
    ..-------------------------------------------------------
    Check  in ./TopQuotes/Data/ 
    -------------------------------------------------------
    .
    ----------------------------------------------------------------------
    Ran 16 tests in 6.386s
    
    OK

## To Exit VirtualEnv:

    deactivate
