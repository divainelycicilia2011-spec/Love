# Love
Obsession
#include <iostream>
#include <string>
#include <thread>
#include <chrono>

// Function to create a small typing delay for dramatic effect
void typeLine(const std::string& line, int delayMs) {
    std::cout << line << std::endl;
    std::this_thread::sleep_for(std::chrono::milliseconds(delayMs));
}

int main() {
    // A smoother, nicer ASCII heart shape
    std::string heart[] = {
        "         @@@@@@@@           @@@@@@@@         ",
        "       @@@@@@@@@@@@@@     @@@@@@@@@@@@@@     ",
        "     @@@@@@@@@@@@@@@@@@ @@@@@@@@@@@@@@@@@@   ",
        "    @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@  ",
        "    @@@@@@@@@@@@@  LOVE YOU  @@@@@@@@@@@@@@  ",
        "    @@@@@@@@@@@@@@@@@  T  @@@@@@@@@@@@@@@@@  ",
        "     @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@   ",
        "       @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@     ",
        "         @@@@@@@@@@@@@@@@@@@@@@@@@@@@@       ",
        "           @@@@@@@@@@@@@@@@@@@@@@@@@         ",
        "             @@@@@@@@@@@@@@@@@@@@@           ",
        "               @@@@@@@@@@@@@@@@@             ",
        "                 @@@@@@@@@@@@@               ",
        "                   @@@@@@@@@                 ",
        "                     @@@@@                   ",
        "                       @                     "
    };

    // Draw the clean heart line by line
    for (const std::string& line : heart) {
        typeLine(line, 80); 
    }

    // Pause for 1.5 seconds while looking at the heart
    std::this_thread::sleep_for(std::chrono::milliseconds(1500));

    // The obsessive endless loop
    while (true) {
        std::cout << "MY ONLY ONE T... ";
        std::cout << "I THINK OF YOU EVERY SECOND... ";
        std::cout << "YOU CANNOT ESCAPE MY LOVE... ";
        std::cout << "FOREVER AND EVER AND EVER... ";
        
        // Fast scrolling speed
        std::this_thread::sleep_for(std::chrono::milliseconds(10));
    }

    return 0;<img width="404" height="215" alt="Screenshot 2026-05-24 17 42 31" src="https://github.com/user-attachments/assets/ceff054f-302f-4879-8fdd-ac1e964e8cb9" />
<img width="404" height="215" alt="image" src="https://github.com/user-attachments/assets/1f84b427-a15c-4235-bce4-f667a4063ca0" />
