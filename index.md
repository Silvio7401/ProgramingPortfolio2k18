# Silvio's 2018 Programing Portfolio
OOP Projects from 2017-18

## Contact Info: Gmail
silviosantini7401@gmail.com

# Group Projects:
### Space Game
  -Our group project for 2017-2018 is a single-player game where the user controls a ship with his mouse and attempts to avoid an enemy ship.
  - Gui mockup
  - ![Gui mockup](https://user-images.githubusercontent.com/26355832/36695422-8c9c630c-1afe-11e8-9d4d-e2f0022949b5.png)
  
  - Running Code
  - ![Running code](https://user-images.githubusercontent.com/26355832/38640418-71fee262-3d91-11e8-979f-ec8e61fca1e3.png)
  
  [Source Code](https://github.com/godofdeathftw/Spaceship-Shooter/tree/master/Game)
	
# Individual Projects:
### Calculator
  - Basic code that renders a calculator where you can hover over buttons uses mouse press features to calculate basic math.
  - ![Calculator](https://raw.githubusercontent.com/Silvio7401/Calculator/master/Calc.png)

[Source Code](https://github.com/Silvio7401/Calculator/tree/master/SRC)

### PigLatin
  - Basic code that converts a typed word into the PigLatin languge varient of it.
```
import java.util.Scanner;

public class PigLatin {
	public static void main(String[] args) {
		Scanner keyboard = new Scanner (System.in);
		String Str1, Str2;
		System.out.print("Enter a Word to translate to Pig Latin: ");
		Str1 = keyboard.nextLine();
		Str2 = Str1.substring(0,1);
		char first = Str1.charAt(0);
		if (first == 'a' || first == 'e' || first == 'i' || first == 'o' || first == 'u') {
			System.out.println("Your new word is: " + Str1.substring(0) + "ay");
		}else {
			System.out.println("Your new word is: " + Str1.substring(1) + Str2 + "ay");
		}

	}
}
```
### Screensaver
  - Code that renders a randomly generated screensaver.
  
  [Source Code](https://github.com/Silvio7401/Screen/blob/master/SRC/ScreenSaver_App.pde)

### Temperature Converter
  - Code that lets you mouse over a celius value and instantly know the corresponding value in Fahrenheit.
  - ![Tempscale](https://raw.githubusercontent.com/Silvio7401/Temp/master/Temp.png)
  
  [Source Code](https://github.com/Silvio7401/Temp/blob/master/SRC/temp_converter.pde)
