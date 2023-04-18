Group Members :
    
     Abdul Qayyum 
     hassan raheem

Project Intro :
    A LAN based 2player checkers game with a multi-threaded server, implemented using Java sockets and JavaFX.


Project Requirements :
    - java run time enviroment with Javafx sdk.
    
Project Modules :
    - Sockets   --> used to create a client-server architecture.
    - Threads   --> used to connect with multiple clients simaltaneously.
    - JavaFX    --> used to build desktop based gui interface.


Project Execution Sequence :
    Open [networkcheckers] folder > Open terminal > Follow the instrunctions and execute the below commands.
    1- Run Server first
    '''
        java --module-path /usr/share/openjfx/lib --add-modules=javafx.base,javafx.controls,javafx.fxml,javafx.graphics,javafx.media,javafx.swing,javafx.web -ea -jar out/artifacts/server/server.jar
    '''
    2- Run 2 instances of clients
    '''
        java --module-path /usr/share/openjfx/lib --add-modules=javafx.base,javafx.controls,javafx.fxml,javafx.graphics,javafx.media,javafx.swing,javafx.web -ea -jar out/artifacts/client/client.jar
'''


Project KeyFeatures :
    1- we can run this game in a LAN without WAN connection.
    2- If someone is newbie in a checkers than we have provided an option so they can know the rules of checkers and play with its opponent.
    3- In on-line game, you see the game from you side, if you play using white, you see from white side, if you play using black, you see from black side. White and black are decided automatically from the server while pairing two players.
    4- If any player closes the game before finishing an on-line game, opponent wins automatically.

Future Work :
    In future we will merge a chat feature in it so user can play more interactively.
        
    


