#include <stdio.h>

int main(int argc, const char * argv[]) {
    int mesai;
    printf("lütfen mesai saatinizi giriniz");
    scanf("%d",&mesai);
    if(mesai<10){
        printf("ücret :%d ",mesai);
        
    }else if(mesai>10 && mesai<20){
        printf("ücret :%d",10*5+(mesai-10)*3);
    
        
    }else{
        printf("ücret=%d",10*5+10*3+(mesai-20)*3);
    }
    
    return 0;
}
