class Test {
    static <T> void printArray(T[] arr) {
        for(T x : arr)
            System.out.print(x + " ");
    }

    public static void main(String[] args) {
        Integer[] a = {1,2,3};
        printArray(a);
    }
}
