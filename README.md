# raspberrypi_digitalchess
Digital chess with Rpi Chess is a game for two players. The chessboard is square in shape divided into 64 (8x8) fields, painted alternately light and dark. Each player at the beginning of the game has 16 chess pieces, of which eight are pawns, one is a pair of hunters, jumpers and cannons, and a king and queen. One player plays with white pieces and the other with black pieces. Chess develops strategic and tactical skills, encourages rationality in decision-making and long-term thinking, and numerous researches confirm many advantages in everyday life that result from playing chess. The advantage of playing chess with a physical interface (and when the computer is in the background) is that it roughly evokes playing with another person. Computer chess programs are good, but for most it is a real experience of playing chess in front of a wooden board. The goal of this project is to make it possible. The aim of the project is to make a model of a digital chess board. The model can be divided into two parts: hardware and software. The presence of a chess piece that has a built-in magnet in it will detect a reed switch located below each chessboard. Gathering information from the reed switch will be done using a Raspberry Pi which will ultimately send an essential record via serial communication to the Stockfish engine in which a graphical interface is built with an algorithm that displays the current state of the board. Prior knowledge in electronics and programming is required to perform this project. Therefore, to gather the necessary knowledge and skills, it is first recommended to make a test project, the so-called. "Noughts and crosses". The reason is that in terms of project implementation, these are similar games with the difference that instead of 9 fields we have 64, and therefore more hardware components, and a slightly more complex program.
