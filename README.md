# Number-of-Employees-Who-met-the-target
    class Solution {
        public int numberOfEmployeesWhoMetTarget(int[] hours, int target) {
            int result = 0;
            for(int i =0; i<hours.length;i++){
                if(hours[i]>=target){result=result+1;}
            }
            return result;
        }
    }
