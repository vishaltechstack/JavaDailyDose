## **The Problem**

Write a Java method that checks whether a given string is a palindrome. A palindrome is a word, phrase, or sequence that reads the same backward as forward (ignoring spaces, punctuation, and capitalization).



## **How to Approach This Problem**

* **Clean the Input:** Before comparing characters, convert the entire string to lowercase and remove any spaces or non-alphanumeric characters so only letters and numbers remain.



* **Use Two Pointers:** Place one index pointer at the very beginning of the cleaned string (0) and another at the very end (length - 1).



* **Compare and Move Inward:** Loop while the left pointer is less than the right pointer. Compare the characters at both positions. If they do not match at any point, immediately return false. If they match, move the left pointer forward and the right pointer backward.



* **Return True:** If the loop finishes without finding any mismatches, return true.



## **Examples**



&#x09;**Input:** "Racecar"



&#x09;**Output:** true (Cleaned: "racecar", reads the same backward)



&#x09;**Input:** "A man, a plan, a canal: Panama"



&#x09;**Output:** true (Cleaned: "amanaplanacanalpanama", reads the same backward)



&#x09;**Input:** "Java Programming"



&#x09;**Output:** false (Cleaned: "javaprogramming", does not match backward)

