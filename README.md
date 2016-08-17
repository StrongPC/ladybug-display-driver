# LadyBug Seven Segment Driver (Hexadecimal Digit display)

![IC in action](https://github.com/prp-e/ladybug-display-driver/blob/master/LBHexDigit.png)

This is a project from [LadyBug Systems](http://ladybugsystems.ir), and this device I made, helps you to connect your LadyBug product to a seven segment display. 

## How to use it?
You need _Logisim_ to open `LBSevSeg.circ` file. It's available in Ubuntu/Debian repositories and it's installable by typing :

```
sudo apt-get install logisim
```
Enjoy!

## How it works?

![Schematics](https://github.com/prp-e/ladybug-display-driver/blob/master/LadyBugSevenSegmentDriver.png)

### Truth table

| Pin |               Function                       |
|-----|:--------------------------------------------:|
| a   | ~X ~Z + ~W Y + ~W X Z + X Y + W ~X ~Y + W ~Z |
| b   | ~W ~X + ~W ~Y ~Z + ~X ~Z + ~W Y Z + W ~Y Z   |
| c   | ~W ~Y + ~W Z + ~Y Z + ~W X + W ~X            |
| d   | ~W ~X ~Z + ~X Y Z + X ~Y Z + X Y ~Z + W ~Y   |
| e   | ~X ~Z + Y ~Z + W Y + W X                     |
| f   | ~Y ~Z + ~W X ~Y + X ~Z + W ~X + W Y          |
| g   | ~X Y + Y ~Z + ~W X ~Y + W ~X + W Z           |

