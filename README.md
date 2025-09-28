# hydrogen to gas(P2G)-storing-capacity-in-a-windmill.
#include<stdio.h>
int main(){
    int energy_stored;
    printf("\n enter energy stored in percentage in the hydrogen power to gas(P2G):");
    scanf("%d",&energy_stored);
    if(energy_stored<=75){
        printf("\nwindmill should be kept on for atleast 2 hours");
    }
    
    else if(energy_stored<=85%){
        printf("windmill to be kept on for atleast 1 hour");

    }
    else if(energy_stored<=95%){
        printf("windmill to be kept on for atleast 30 mins");

    }
    else if(energy_stored==100%){
        printf(“hydrogen power to gas(PG2) capacity to store energy is full hence windmill to be switched off");
    }
    else{
        printf("enter agin");
    }
    return 0;
    }
    

    
    return 0;
}
