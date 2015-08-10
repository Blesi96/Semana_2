# Semana_2
Respuestas seguimiento
//volumen es pi*radiocuadrado por la altura
            //area 2pi radio *(altura+radio)
            /*  C1 
                string r, h;
                double v, a,radio,altura;
                do{
                Console.WriteLine("ingrese el radio, si quiere salir escriba exit \n");
                r = Console.ReadLine();
                Console.WriteLine("ingrese la altura \n");
                h = Console.ReadLine();
                if (double.TryParse(r, out radio) && double.TryParse(h, out altura))
                {
                    v = (Math.PI * (radio * radio) * altura);
                    a = 2 * Math.PI * radio * (altura + radio);
                    Console.WriteLine("el volumen es " + v);
                    Console.WriteLine("el area es " + a);
                }
                else {
                    Console.WriteLine("ingrese un numero la proxima vez \n");
                }}while(r != "exit");*/
                
                

            //C2
            /* int a = 7;
             int b = 2;
             float c = 4;
             float d = 3;
             float result = (float)((float)(a) / (float)(b)) + (c / d);
             Console.WriteLine(result);
             Console.ReadKey();
             */
            /*    short a = 30000;
               short b = 30000;
                short sum= (short)(a+b);
                Console.WriteLine("el resultado es " + sum);
                Console.ReadKey();
                */
                
                

            /* punto 14
            int[] scores = new int[10] { 100,95, 92, 87, 55, 50, 48, 40, 35, 10 };
                Console.WriteLine(scores[5]);
                Console.ReadKey();
              */
              
              

            //C3
            /*
                        int[] datos=new int[] {4,51,-7,13,-99,15,-8,45,90};
                        int i=0;
                        int mayor, menor;
                        mayor = datos[0];
                        menor = datos[0];
                        foreach (int element in datos)
                        {
                            if (i < 8)
                            {
                                if (datos[i] < datos[i + 1])
                                {
                                    i++;
                                    if (mayor < datos[i])
                                    {
                                        mayor = datos[i];
                                    }
                                }else{
                                i++;
                                if (datos[i] < menor)
                                {
                                    menor = datos[i];
                                }
                            }
                            }
                
                        }Console.WriteLine("el mayor es "+mayor+"\n el menor es "+menor);
            
                        Console.ReadKey();
                        */
                        
                        
            //P23
            /*  int[] a = new int[] { 1, 2, 3 };
               int[] b = a;
               b[0] = 17;
               Console.WriteLine(a[0]);
               Console.ReadKey();*/
               
               

            // p24
            /*Console.WriteLine("ReturnValue() es: {0}", ReturnValue());
            Console.WriteLine("ReturnValue() es: {0}", ReturnValue2());
            Console.ReadKey();
        }
        public static int ReturnValue()
        {
            int x = new int();
            x = 3;
            int y = new int();
            y = x;
            y = 4;
            return x;
        }
        public static int ReturnValue2()
        {
            Myint x = new Myint();
            x.MyValue = 3;
            Myint y = new Myint();
            y = x;
            y.MyValue = 4;
           return x.MyValue;}
            */
            
            
            
            C4
            {
    class Program
    {
        static void Main(string[] args)
        {
            int dia;
      Console.WriteLine("Escriba un número del 1 al 7");
      dia = Convert.ToInt16(Console.ReadLine());

            switch (dia)
            {
                case 1:
                Console.WriteLine("Domingo");
                break;

                case 2:
                Console.WriteLine("Lunes");
                break;

                case 3:
                Console.WriteLine("Martes");
                break;

                case 4:
                Console.WriteLine("Miercoles");
                break;

                case 5:
                Console.WriteLine("Jueves");
                break;

                case 6:
                Console.WriteLine("Viernes");
                break;

                case 7:
                Console.WriteLine("Sábado");
                break;

                default:
                Console.WriteLine("Ingrese un númervo valido");
                break;

            }


            Console.ReadLine();            
        }

        
    }
}

            
