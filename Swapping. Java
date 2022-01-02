import java.io.DataInputStream;
import java.io.IOException;
class Swapping
{
	public static void main(String args[])
	{
		int fno=0,sno=0,temp=0;
		System.out.println("Swapping of Two Number");
		DataInputStream d = new DataInputStream(System.in);
		try
		{
			System.out.print("Enter the value of FNO = ");
			fno=Integer.parseInt(d.readLine());
			System.out.print("Enter the value of SNO = ");
			sno=Integer.parseInt(d.readLine());
		}
		catch(IOException ioe)
		{}
		System.out.println("Before swapping of value of FNO = "+ fno + " SNO = " +sno);
		temp=fno;
		fno=sno;
		sno=temp;
		System.out.println("After swapping of value of FNO = "+ fno + " SNO = " +sno);

	}
}
