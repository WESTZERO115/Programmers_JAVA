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
//다른 사람들 보니까 수학공식 이용하니까 훨씬 간단한 듯 보였다. (수열의 합)
