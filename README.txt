/**
 * StAuth10244: I Nishkarsh Dubb, 000838587 certify that this material is my original work. 
 * No other person's work has been used without due acknowledgement. I have not made my work available to anyone else.
 */

Marking Breakdown
App is similar to the clone of inshorts app (done)

1. Purpose or target user	5 -> Tech news users (done)

2. Web service 	15 -> https://newsapi.org/ (done)

3. Web service parameter	15-> (done)
           params:{
              
               q: searchText,
               category:"technology",
               
           }

        
            params:{
                category: "technology",
                
            }

Link to the documentation: https://newsapi.org/docs 

4. React Native components	25 -> Done (Meets all the requirements)

5. Well-designed and professional in appearance	10 -> made it look very close to the in shorts app (done)

6. Exceeds minimum requirements in a way that is meaningful to the purpose of the application	10

7. Demo video	20 -> (done) (video included in the zip file)

---------------------
Create a React Native application with a well-defined purpose and/or target user in-mind.  The exact purpose and/or target user is up to you, but try to find an idea you find fun!
e.g. an application that allows users to access weather report data.
e.g. an application that allows users to access hockey statistics.
e.g. an application that allows users to access Pokémon data.
(done created a tech news app similar to inshorts-> Additional resources used: https://www.youtube.com/watch?v=5Ko7B3G4U04 | https://www.youtube.com/watch?v=pwZGs-4lJbM | https://www.youtube.com/watch?v=0QRwlJRgM8w | https://medium.com/mesan-digital/how-to-build-a-news-app-with-react-native-app-part-1-e78d7d3c55b3)

Your application must allow the user to perform actions (e.g. button presses, etc.) that will result in data being retrieved from a web service and being displayed in a neatly formatted way to the user.
You may use multiple web services and/or multiple web service endpoints if you prefer, but only accessing one web service at one endpoint is required.   (done through home and search button)

At least one parameter must be used when accessing at least one endpoint of the webservice, and this parameter must be different depending on what input the user provides or what actions the user takes.
e.g. a parameter might be set based on what a user has typed into a TextInput (done through search bar)
e.g. a parameter might be set based on which button a user has clicked (done through home button, when the screen loads)

The application must incorporate a minimum of the following: (meets all the requirements)
At least one List View component  (used flatlist)
You can use any of the different types of List View components.
At least one TextInput component (used it in search bar)
At least two Button components (home and search button)
At least one image (used image in the article component)
At least one usage of Flexbox to layout the application (flexbox is applied)
------------

Additional Comments:
All in all this was a pretty fun app to create, and I learnt a lot about react native and expo in this app.

Additional API key if you get the error: LOG  [AxiosError: Request failed with status code 429]
The error message Request failed with status code 429 indicates that you are making too many requests to the server and it is rate-limiting you.

API KEY-> 46b7b8866dc347e0b9027262beabf2b5
#USED Android studio emulator to run the app