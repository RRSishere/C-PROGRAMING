# include<stdio.h>
# include<ctype.h>
# include<math.h>

int main(){
    for(int i=3;i<=10;i++){
        for(int j=2;j<i;j++){
            if(i%j==0){
                continue;
                
            }else{
                printf("%d",i);
            }
        }
    }

    
    return 0;
}
