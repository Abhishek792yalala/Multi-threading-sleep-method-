# Multi-threading-sleep-method-
// Using multiple threads and sleep method

class Code{

    public void run(){

        while (true){

            try{

                Thread.sleep(3000);

            }

            catch (Exception e){

                System.out.println(e);

            }

            System.out.println("Welcome to the java programming");

        }

    }

}

class compile extends Code{

    public void runn(){

        while (true){

            try{

                Thread.sleep(40);

            }

            catch (Exception e){

                System.out.println(e);

            }

            System.out.println("Your code is ready to execute");

        }

    }

}

class Java{

    public static void main(String... java){

        Code c=new Code();

        c.run();

        compile f=new compile();

        f.runn();

    }

}
