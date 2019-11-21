# Strong-Password
Louise joined a social networking site to stay in touch with her friends. The signup page required her to input a name and a password. However, the password must be strong. The website considers a password to be strong if it satisfies the following criteria:

Its length is at least 6.
It contains at least one digit.
It contains at least one lowercase English character.
It contains at least one uppercase English character.
It contains at least one special character. The special characters are: !@#$%^&*()-+
She typed a random string of length n in the password field but wasn't sure if it was strong. Given the string she typed, can you find the minimum number of characters she must add to make her password strong?

Note: Here's the set of types of characters in a form you can paste in your solution:

numbers = "0123456789"
lower_case = "abcdefghijklmnopqrstuvwxyz"
upper_case = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
special_characters = "!@#$%^&*()-+"

Sample Input 0

3
Ab1
Sample Output 0

3
Explanation 0

She can make the password strong by adding 3 characters, for example, $hk, turning the password into Ab1$hk which is strong.

2 characters aren't enough since the length must be at least 6.

HackerRank: https://www.hackerrank.com/challenges/strong-password/problem?h_r=next-challenge&h_v=zen
