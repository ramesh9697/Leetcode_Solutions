# Leetcode_Solutions
class Solution {
    public boolean isPalindrome(int x) {
      int y=0;
      int z=0;
      int a=x;
      while(x>0){
          y=x%10;
          z=z*10+y;
          x=x/10;
      }  

      if(z==a){
          return true;
      }
      else{
         return false;
      }
    }
}
