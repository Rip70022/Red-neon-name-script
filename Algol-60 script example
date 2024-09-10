begin
  (* Procedure to initialize an array *)
  procedure initialize_array(a, n);
  value n;
  integer a, n;
  integer i;
  
  begin
    for i := 0 step 1 until n - 1 do
      a[i] := i + 1
  end;

  (* Procedure to print an array *)
  procedure print_array(a, n);
  value n;
  integer a, n;
  integer i;
  
  begin
    for i := 0 step 1 until n - 1 do
    begin
      print(a[i]);
      print(" ")
    end;
    print("\n")
  end;

  (* Function to compute the sum of an array *)
  integer function sum_array(a, n);
  value n;
  integer a, n;
  integer i, sum;
  
  begin
    sum := 0;
    for i := 0 step 1 until n - 1 do
      sum := sum + a[i];
    sum_array := sum
  end;

  (* Function to compute the average of an array *)
  real function average_array(a, n);
  value n;
  integer a, n;
  integer sum;
  
  begin
    sum := sum_array(a, n);
    average_array := sum / n
  end;

  (* Function to find the maximum element in an array *)
  integer function max_array(a, n);
  value n;
  integer a, n;
  integer i, max;
  
  begin
    max := a[0];
    for i := 1 step 1 until n - 1 do
      if a[i] > max then
        max := a[i];
    max_array := max
  end;

  (* Procedure to find the index of a given element *)
  integer function index_of(a, n, key);
  value n, key;
  integer a, n, key;
  integer i;
  
  begin
    index_of := -1;  (* Default to -1 if not found *)
    for i := 0 step 1 until n - 1 do
      if a[i] = key then
        index_of := i
  end;

  integer array a;
  integer n;
  real avg;
  integer sum, max, key, index;

  (* Initialize and use the array *)
  n := 10;
  integer i;

  (* Allocate array and initialize *)
  a[0] := 0;
  a[1] := 0;
  a[2] := 0;
  a[3] := 0;
  a[4] := 0;
  a[5] := 0;
  a[6] := 0;
  a[7] := 0;
  a[8] := 0;
  a[9] := 0;

  initialize_array(a, n);

  (* Print the array *)
  print("Array: ");
  print_array(a, n);

  (* Calculate and print the sum *)
  sum := sum_array(a, n);
  print("Sum of elements: ");
  print(sum);
  print("\n");

  (* Calculate and print the average *)
  avg := average_array(a, n);
  print("Average of elements: ");
  print(avg);
  print("\n");

  (* Find and print the maximum element *)
  max := max_array(a, n);
  print("Maximum element: ");
  print(max);
  print("\n");

  (* Search for a specific element and print its index *)
  key := 5;  (* Element to search for *)
  index := index_of(a, n, key);
  if index <> -1 then
  begin
    print("Element ");
    print(key);
    print(" found at index ");
    print(index);
    print("\n")
  end
  else
    print("Element ");
    print(key);
    print(" not found\n")
end
