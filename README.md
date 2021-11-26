# m-pow-n-using-recursion

    int power(int m, int n){
      if (n==0)
        return 1;
      return power(m,n-1)*m;
    }

    void main(){
      int n,m;
      scanf("%d%d", &m,&n);
      int result = power(m,n);
      printf("%d", result);
    }
