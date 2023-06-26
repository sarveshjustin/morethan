# morethan
```
module ThreeBitComparator(input [2:0] bits, output reg out);

  always @(*)
  begin
    if (bits[0] + bits[1] + bits[2] > 1)
      out = 1;
    else
      out = 0;
  end

endmodule
```
```
module ab (a,b,c,f);
  input a,b,c;
  output f;
assign f = (a&c) | (b&c) | (a&b);
endmodule
```
