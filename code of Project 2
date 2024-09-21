import java.util.Scanner;

class Project2
{
    public static void main(String args[])
    {
    	/* This program assumes that the student has 5 subjects,
    	 * thats why I have created the array of size 5. You can
    	 * change this as per the requirement.
    	 */
        int marks[] = new int[5];
        int i;
        float total=0, avg;
        Scanner scanner = new Scanner(System.in);
		
        
        for(i=0; i<5; i++) { 
           System.out.print("Enter Marks of Subject "+( i+1 )+":");
           marks[i] = scanner.nextInt();
           total = total + marks[i];
        }
        scanner.close();
        //Your result is Here
        System.out.println("Your Result is Here : ");
        // Total Marks 
        System.out.println("Your total marks is = "+ total);
        // Average percentage 
        System.out.println("The Average Percentage of marks is = "+ total/5);
        //Grade
        avg = total/6;

        System.out.print("The student Grade is: " );

        if(avg>=80)
        {
            System.out.print("A");
        }
        else if(avg>=60 && avg<80)
        {
           System.out.print("B");
        } 
        else if(avg>=40 && avg<60)
        {
            System.out.print("C");
        }
        else
        {
            System.out.print("D");
        }
    }
}
