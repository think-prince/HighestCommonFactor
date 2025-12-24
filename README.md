# HighestCommonFactor
#code for H.C.F

public class HighestCommonFactor {
    public static int HCF(int x, int y){
        int fact =1, i =1;
        int z= Math.min(x,y);
        while(i<=z){
            if ((x%i ==0) && (y%i==0)){
               fact =i;
            }
            i++;
        }
        return fact;
    }
}
