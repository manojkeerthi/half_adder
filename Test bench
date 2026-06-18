
module half_adder_tb;
  reg a;
  reg b;
  wire s;
  wire c;
  
  half_adder d1(.a(a),.b(b),.s(s),.c(c));
  initial begin
    #10;
    a=0; b=0;#10; $display("A=%b B=%b Sum=%b Carry=%b", a, b, s, c);
    a=0; b=1;#10; $display("A=%b B=%b Sum=%b Carry=%b", a, b, s, c);
    a=1; b=0;#10; $display("A=%b B=%b Sum=%b Carry=%b", a, b, s, c);
    a=1; b=1;#10; $display("A=%b B=%b Sum=%b Carry=%b", a, b, s, c);
   $finish;
  end
 
endmodule
