#include <cmath>
class Solution
{
public:
	int reverse(int x) {


		//正负
		int rev = 0;
		for (; x; rev = rev * 10 + x % 10, x /= 10)
		{
			//溢出判断
			if (rev > INT_MAX / 10 || (rev == INT_MAX / 10 &&  (x%10) > 7)) return 0;
			if (rev < INT_MIN / 10 || (rev == INT_MIN / 10 && (x % 10) < -8)) return 0;

		}	
		
		return rev;

	}
};
