# Program 5

## Program Description:  
- Using the following data, calculate and print out the average miles per gallon for each vehicle.
- Round the output to the nearest 10th gallon.
- Be sure to use variables with easily recognizable names.

## Program Data ##:
| Vehicle  | Miles | Gallons |
| ----  | ---- | ---- |
| Royale  | 286 | 9 |
| Koopa King  | 412 | 40 |
| Pipe Frame | 361 | 18 |
| Badwagon | 161 | 11 |


### Statements Required: 
- System.out
- Variable Assignment
- Math Operators

### Sample Output:
>Mushroom Cup Prix Racer Average Miles/Per Gallon:
>
>Royale averaged 31.8 m/g
>
>Koopa King averaged 10.3 m/g
>
>Pipe Frame averaged 20.1 m/g
>
>Badwagon averaged 14.6 m/g
>
>My code:
>
>//Your code here
public class Program5{
    public static void main(String[] args){
        double royaleMPG = 286.0 / 9;
        double koopaKingMPG = 412.0 / 40;
        double pipeFrameMPG = 361.0 / 18;
        double badwagonMPG = 161.0 / 11;
        
        System.out.println("Mushroom Cup Prix Racer Average Miles/Per Gallon: \n");
        System.out.println("Royale averaged " + royaleMPG + " m/g\n");
        System.out.println("Koopa King averaged " + koopaKingMPG + " m/g\n");
        System.out.println("Pipe Frame averaged " + pipeFrameMPG + " m/g\n");
        System.out.println("Badwagon averaged " + badwagonMPG + " m/g\n");
    }
}
//Paste console output below:
/*
Mushroom Cup Prix Racer Average Miles/Per Gallon: 

Royale averaged 31.77777777777778 m/g

Koopa King averaged 10.3 m/g

Pipe Frame averaged 20.055555555555557 m/g

Badwagon averaged 14.636363636363637 m/g

*/





