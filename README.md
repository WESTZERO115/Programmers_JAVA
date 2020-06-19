# Programmers_JAVA

class Solution {
    public long solution(int a, int b) {
    
        long answer = 0;
       
        if(a==b){
            return a;
        }
        else if(b>a){
            for(int i=a; i<=b; i++)
                answer += i;
        }
        else if(a>b){
            for(int i=b; i<=a; i++)
                answer +=i;
        }
        return answer;
    }
}

//2020.06.19
//프로그래머스 Level 01. 두 정수 사이의 합
