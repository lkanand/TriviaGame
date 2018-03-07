# Comic Book Trivia

This is a ten question trivia game that will test your knowledge about comic book heroes and villains. Since I am not actually very knowledgeable about comic books I had to rely on <a href = "https://www.usefultrivia.com/comic_book_trivia/">this site</a> to compile the game's question bank.  

## How to Play

To begin playing this trivia game, click <a href = "https://lkanand.github.io/TriviaGame">here</a>. You will have 25 seconds to answer each multiple choice question. After selecting your response or running out of time, the game will display a GIF that is relevant to the question. If your response was correct, it will also display a famous superhero quote. Otherwise, it will notify you that you either answered incorrectly or ran out of time.

After going through ten questions, the game will display your final results (correct answers, incorrect answers and questions unanswered). To play again, click anywhere on the screen.   

## Development

Comic Book Trivia was created using a combination of HTML, CSS, JavaScript, jQuery and Ajax. It uses jQuery event handlers and the `setTimeout` and `setInterval` functions to cycle between displaying the question and the correct answer. The program sends Ajax requests to the GIPHY API in order to display GIFs of comic book characters. 
