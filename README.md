# Reverse-an-array

 int arr[]= {4,6,5,2};
       
          
      int temp=0;
      int start=0;
      int end= arr.length-1;
      
      
      while(start<end)
      {
        temp = arr[end];
        arr[end] = arr[start];
        arr[start]= temp;
        
        start++;
        end--;
      }
      
      
      for(int i=0; i<arr.length; i++)
      {
        System.out.print(" "+arr[i]);
      }
