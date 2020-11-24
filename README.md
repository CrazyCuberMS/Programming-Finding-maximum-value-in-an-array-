# Programming || Finding maximum value in an array

#include iostream

int main()

{

    int a;
    
    std::cin >> a;
    
    int ar[a];
    
    for (int i=0; i<a; i++){  std::cin >> ar[i]; }
    int max = 0;
    for (int k=0; k<a; k++) { if( max< ar[k]) { max = ar[k];} }
    
    std::cout << max;
    
    return 0; 
}
