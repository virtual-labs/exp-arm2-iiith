Implement the following C-procedures in ARM. You can assume the parameters are passed either in registers or through the stack.

1.  swap(int *a, int *b)
    {
     int temp;
     temp = *a;
     *a = *b;
     *b = temp;
    }

2. Write a sorting routine with signature Sort(int *data, int dim) where dim gives the dimension of the array 'data'. Use the swap routine you have written earlier in the Sort routine.

