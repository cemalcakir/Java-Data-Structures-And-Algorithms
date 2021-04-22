public class SelectionSort {
	public static int smallestFromIndex(int[] array, int index) {
		for (int i = index; i < array.length; i++) {
			if (array[i] < array[index]) {
				index = i;
			}
		}
		return index;
	}
	
	public static void swap(int[] array, int index1, int index2) {
        int temp = array[index1];
        array[index1] = array[index2];
        array[index2] = temp;
	}
	
	public static void selectionSort(int[] array) {
		for (int i = 0; i < array.length; i++) {
			swap(array, i, smallestFromIndex(array, i));
		}
	}
}
