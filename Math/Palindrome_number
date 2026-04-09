// Checks if an integer is palindrome
class Solution {
    public boolean isPalindrome(int x) {
        int temp;
        if(x<0){
            temp=-1*x;
        }
        else{
            temp=x;
        }
        int sum=0;
        while(x!=0){
            int rem=x%10;
            sum=(sum*10)+rem;
            x=x/10;
        }
        if(sum==temp){
            return true;
        }
        else{
            return false;
        }
    }
}
