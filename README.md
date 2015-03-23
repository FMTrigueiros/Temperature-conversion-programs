# Temperature-conversion-programs
Programs
T = temperature
c = celsius
f = fahrenheit

1) The formula to convert fahrenheit to celsius is:
Tc = (Tf - 32) * 5/9

2) The formula to convert celsius to fahrenheit is:
Tf = Tc * 9/5 + 32


For the script we will first define a class:

3) in this case the class will be Numeric: class Numeric

4) then we define the variable, we can call it fahrenheit_to_celsius: def fahrenheit_to_celsius

Then we attribute the self variable which indicates the input value. Self will be the value we are looking to convert.

5) We type self and the formula in front so that the conversion will take place: (self - 32) * 5 / 9
6) we then say end to finish the first def: end

7) we repeat the same process for the inverted formula, now we do celsius_to_fahrenheit:
def celsius_to_fahrenheit
    self * 9/5 + 32
    end

8) finally we end the class by typping end: end


The total script will be the following: 

class Numeric
      def fahrenheit_to_celsius
          (self - 32) * 5/9
      end
      def celsius_to_fahrenheit
          self * 9/5 + 32
      end
end

