# palindrome
class Solution {
    public boolean isPalindrome(int x) {
     int a,m,s=0;
        m=x;
         if(x==0) return true;
        if(x<0 || x%10==0) return false;
        while(x!=0)
        {
            a=x%10;
            s=s*10+a;
            x=x/10;
        }
        if(s==m)
            return (true);
        else
            return(false);
    }
}   
