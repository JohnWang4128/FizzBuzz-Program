# FizzBuzz-Program
Write a program that prints numbers from 1 to 100. But for multiples of:
3, print "Fizz" instead of the number,
5, print "Buzz",
For numbers divisible by both 3 and 5, print "FizzBuzz“

#First, I made sure I understood what the problem was asking. I needed to print numbers from 1 to 100, but replace certain ones with specific words based on whether they’re divisible by 3, 5, or both I made sure I understood what the problem was asking. I needed to print numbers from 1 to 100, but replace certain ones with specific words based on whether they’re divisible by 3, 5, or both

#Then I broke the logic into parts: If a number is divisible by both 3 and 5 → print 'FizzBuzz' If divisible by just 3 → print 'Fizz' If divisible by just 5 → print 'Buzz' Otherwise → print the number itself.

#Since I needed to go through numbers 1 to 100, I used a for loop with range(1, 101).”

#Inside the loop, I used if-elif-else statements to check for the conditions I listed earlier. I made sure to check for ‘FizzBuzz’ first — that is, numbers divisible by both 3 and 5 — to avoid overlapping with the separate checks for just 3 or just 5.

#I ran the code and looked over the output to confirm it worked as expected. I specifically checked numbers like 3, 5, 15, and 30 to make sure they printed 'Fizz', 'Buzz', and 'FizzBuzz' correctly.
