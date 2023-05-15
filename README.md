# Checkpoint-Recursion
function isPalindrome(word) {
  let left = 0;
  let right = word.length - 1;
  
  while (left < right) {
    if (word.charAt(left) !== word.charAt(right)) {
      return false;
    }
    left++;
    right--;
  }
  
  return true;
}
