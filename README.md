# Program-to-print-the-char-value-from-ascii-no
public class Arrays {
	public static void main(String[] args) {
		int []asciiarray= {96,97,98,99,100,101,102,103,104,105};
		for (int i=0;i<asciiarray.length;i++)
		{
			
			System.out.println((i+1)+" "+(char)asciiarray[i]);
		}
		for (int i=0;i<256;i++)
		{
			System.out.println((i+1)+" "+(char)i);
		}
		


}
}
