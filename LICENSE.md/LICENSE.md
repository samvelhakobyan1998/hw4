1.public static int sum(int array[]) {
int result = 0;
for (int i = 0; i < array.length; i++)
result += array[i];
return result;

}

public static int max(int array[]) {
int result = array[0];
for (int i = 1; i < array.length; i++)
if (array[i] > result)
result = array[i];
return result;

}

public static int maxSum(int array[]){ 


		int result = 0;
		
		for(int element: array)
			result += element;
		
		return result;

}

System.out.println(max(arr));

2.public static void swap(int array[], int from, int to) {
int temp = array[from];
array[from] = array[to];
array[to] = temp;

}

public static void reverse(int array[]) {
for (int i = 0; i < array.length / 2; i++)
swap(array, i, array.length-1-i);

}

public static void shift(int array[], int offset) {

int[] backward = new int[len]; 
		for (int i = 0; i < backward.length; i++)
			backward[i] = backward.length - i - 1; 
		for (int i = 0; i < backward.length; i++)
    }
    
    
			System.out.print(backward[i] + " "); 
		System.out.println("\n");
