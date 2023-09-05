# 🕒 A simple Stopwatch in C 

👋 Welcome to the Simple Stopwatch project in C!🕐This minimalistic stopwatch application is designed to provide users with a straightforward and easy-to-use time-tracking tool.Feel free to explore the code, contribute, or use it in your own projects. Happy timing!⌛🚀

## Mechanics of the stopwatch:

* main() - is the main function (the entry point of the watch)
* sleep() - pauses the execution for a specified number of seconds (in this case for 1 second)
* fflush() - clears the output buffer in gcc
* system() - clears the output on screen
        * for windows use system("cls")
        * for linux/unix systems use system("clear")
* !!! The pause, resume, new and end features are still missing and will be added soon !!!

## How to run the stopwatch:

To run the stopwatch you can simply compile it in your IDE or follow these simple steps:
1. Run the command: gcc -o stopwatch *.c (on your terminal) || Alternatively, you can simple use the provided stopwatch.exe 
2. Paste: ./stopwatch
3. To end the stopwatch simply press: ctlr + c 
                                !!!Enjoy!!!

### Author
- [Ipfani Muleya](https://github.com/ipfanimuleya)