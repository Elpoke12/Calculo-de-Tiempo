# Calculo-de-Tiempo
 int suma=0;
			TimeSpan stop;
			TimeSpan start = new TimeSpan(DateTime.Now.Ticks);
            for (int i = 0; i < 1000000;i++)
            {
                suma = suma + i;
            }
            Console.WriteLine("El resultado de la suma es {0} ",suma);
			stop = new TimeSpan(DateTime.Now.Ticks);
            Console.Write(stop.Subtract(start).TotalSeconds); Console.Write(" Segundos ");

            Console.ReadKey();
	
	
	
