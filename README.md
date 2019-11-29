#include<stdio.h>
#include<stdlib.h>
#pragma warning(disable: 4996)


/* 하앍. */

/* ------------------------------------ 
1.  반복문 넣어야함. 주석달았음.
2.  while문 안에 조건 넣어야함.
3.  학점인 hakjum과 jumsu_output 실수형으로 바꾸어야함.
 ------------------------------------ */


int main(void){
	// hacki를 굳이 배열로 받아야하는지 모르겠음..!
	int hacki[20],hakjum[30],grade[30],jumsu_output[20],grade_output[20];
	int i=0;
	char ch;
	printf("~ 학기 학점,등급,신청학점을 입력해주세요.");
	// 반복문 필요함.
	scanf("",hacki[],hakjum[],grade[]);

	jumsu_output += hakjum[]; //  학점 평균계산용
	grade_output += grade[] // 이수학점



	printf("더 입력할 학기가 있으신가요? ( Y / N )\n"); 
	// Y / N 응답을 통해 종료여부를 묻는다.
	ch = getchar();
	while(ch !=  || ch != );


	if(jumsu_output > 4.0) // 학점 비교 스탙흐
		printf("학점 A+"); 
		// 내가보기엔 학점 if문을 switch로 바꿔도 ㄱㅊ을듯.
	else if(jumsu_output > 3.5)
		printf("학점 A0");
	else if(jumsu_output > 4.0)
		printf("학점 B+");
	else if(jumsu_output > 3.5)
		printf("학점 B0");
	else if(jumsu_output > 3.0)
		printf("학점 C+");
	else if(jumsu_output > 2.5)
		printf("학점 C0");
	else if(jumsu_output > 2.0)
		printf("학점 D+");	
	else if(jumsu_output > 1.5)
		printf("학점 D0");
	else
		printf("학점 F");	


}
