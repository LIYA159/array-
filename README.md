# array-
{

                int n = Convert.ToInt32(Console.ReadLine());
                int[] a = new int[n];
                Random rnd = new Random();
                for (int i = 0; i < a.Length; i++)
                {
                    a[i] = rnd.Next(0, 100);
                    Console.Write(a[i] + " ");

                }
                int g;
                    Console.WriteLine();

                    int b = a.Min();
                    int c = Array.IndexOf(a, b);
                    int y = a.Max();
                    int v = Array.IndexOf(a, y);
                    g = b + y;
                    Console.Write(b+"+"+y+"="+g);
                Console.ReadLine();
            }
        }
    }
}
      
