# ConstructorChallenge
package academy.learnprogrmming;

public class VipCustomer {
    String name, emailAddress;
    Double creditLimit;

    public VipCustomer(String name, String emailAddress, Double creditLimit){
        this. name = name;
        this.emailAddress = emailAddress;
        this.creditLimit = creditLimit;
    }

    public Double getCreditLimit() {
        return creditLimit;
    }
    public String getName(){
        return name;
    }
    public String getEmailAddress(){
        return emailAddress;
    }
}
package academy.learnprogrmming;

public class Main {

    public static void main(String[] args) {

        VipCustomer empty = new VipCustomer("default name " , " Default email address " , 0.0);

        VipCustomer second = new VipCustomer("default name " , " vasser48@gmail.com " , 0.0);

        VipCustomer third = new VipCustomer("Yowesy " , " vasser48@gmail.com " , 1000.00);

        System.out.println(empty.getName() + empty.getEmailAddress() + empty.getCreditLimit());
        System.out.println(second.getName() + second.getEmailAddress() + second.getCreditLimit());
        System.out.println(third.getName() + third.getEmailAddress() + third.getCreditLimit());





    }
}

"C:\Program Files\Java\jdk-15.0.1\bin\java.exe" "-javaagent:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\lib\idea_rt.jar=53188:C:\Users\nadiy\OneDrive\Desktop\IntelliJ IDEA Community Edition 2020.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\nadiy\IdeaProjects\VipCustomerChallenge\out\production\VipCustomerChallenge academy.learnprogrmming.Main
default name  Default email address 0.0
default name  vasser48@gmail.com 0.0
Yowesy  vasser48@gmail.com 1000.0

Process finished with exit code 0

