# PanDigital numbers test
This is a recreational math program.
It's not interactive in any way. The program runs through a list of numbers, checks which of them fulfill a condition and writes them in a file.

**Numbers that are being checked:**
All *pandigital* numbers.

'Pandigital' numbers (**PDNs**) a numbers that contain all digits (1..9). As the definition may vary, I have chosen numbers that do not contain zero or duplicate digits. All checked numbers contain all 9 digits from 1 to 9, each only once per number.

**Condition to checke the PDNs against:**
For N going from 1 to 9, if the currently checked PDN, cut at the Nth digit, divides the Nh digit (no remainder), the PDN is considered passed the test.

**Example:**
- 123648759 is divisible by 9 (result: 13738751)
- 12364875 is divisible by 5 (result: 2472975)
- 1236487 is divisible by 7 (result: 176641)
- 123648 is divisible by 8 (result: 15456)
etc.

**Note:**
This Numberphile video ["Why 381,654,729 is awesome"](https://www.youtube.com/watch?v=gaVMrqzb91w) is about the PDNs and includes an example of a similar test - whether the PDN, cut at the Nth digit is divisible by N
This program is inspired by the video and I wrote it only for exercise. 
