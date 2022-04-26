# Array-basic
Reverse Order array print
            int [] a = new int [5];
            int n = 5;
            int i;
            Console.WriteLine("Enter 5 Numbers");
            for (i = 0; i < n; i++)
            {       
               a[i]=Convert.ToInt32(Console.ReadLine()); 
            }
            Console.WriteLine("Reverse Order Array is");
            for ( i= n-1; i >=0;i--)
            {
                
                Console.WriteLine("{0}",a[i]); //reverse order stored in array
            }
            Console.WriteLine();
      
 
