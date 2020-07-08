# -
package package02;

public class Chenfa {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int i,j;
		for(i=1;i<10;i++) {
			for(j=1;j<=i;j++) {
				System.out.print(i+"*"+j+"="+i*j+"\t");
				if(j==i)
					System.out.print("\n");
			}
		}

	}

}
