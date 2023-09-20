# CBSE-CALCULATOR
ITS MY FIRST EVER PROJECT CODE 
Public class cbse_calculator {
    public static void main(String[] args) {
        Scanner Scan = new Scanner(System.in);
        System.out.println("Enter your pysics marks:");
        int physics = Scan.nextInt();
        System.out.println("enter your english marks:");
        int english = Scan.nextInt();
        System.out.println("enter your chemistry marks:");
        int chemistry = Scan.nextInt();
        System.out.println("enter your maths marks:");
        int maths = Scan.nextInt();
        System.out.println("enter your computer marks:");
        int computer = Scan.nextInt();

        float percentage=((physics + english + chemistry + maths + computer)/500.0f)*100;

        System.out.println("percentage:");
        System.out.println(percentage);
    }
}
