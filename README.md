ID:124444
name:mohamed




ublic class StackArray<T> {
    private static final int capacity = 2;
    private int top;
    private T[] stack;

    StackArray() {
        this(capacity);
    }

    StackArray(int size
