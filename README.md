class Solution {
    public boolean isPowerOfTwo(int n) {
        return n > 0 && (n & (n - 1)) == 0;
    }
}
public class Main {
    public static void main(String[] args) {
        Solution solution = new Solution();
        System.out.println(solution.isPowerOfTwo(1));  
        System.out.println(solution.isPowerOfTwo(2));
        System.out.println(solution.isPowerOfTwo(3));  
    }
}
