# CBSE-CALCULATOR
ITS MY FIRST EVER PROJECT CODE 
<br>
Public class cbse_calculator {
<br>
    public static void main(String[] args) {
    <br>
        Scanner Scan = new Scanner(System.in);
        <br>
        System.out.println("Enter your pysics marks:");
        <br>
        int physics = Scan.nextInt();
        <br>
        System.out.println("enter your english marks:");
        <br>
        int english = Scan.nextInt();
        <br>
        System.out.println("enter your chemistry marks:");
        <br>
        int chemistry = Scan.nextInt();
        <br>
        System.out.println("enter your maths marks:");
        <br>
        int maths = Scan.nextInt();
        <br>
        System.out.println("enter your computer marks:");
        <br>
        int computer = Scan.nextInt();
        <br>

        float percentage=((physics + english + chemistry + maths + computer)/500.0f)*100;
        <br>

        System.out.println("percentage:");
        <br>
        System.out.println(percentage);
        <br>
    }
    <br>
}
