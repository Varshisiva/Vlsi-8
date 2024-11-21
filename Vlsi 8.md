# Vlsi-8
module counter(

    input clk,

    input rst,

    output reg [3:0] out

    );



always @ (posedge clk or rst) begin

if (rst)

	out=0;

else if (clk==1) 

	out=out+1;

end

	

endmodule

