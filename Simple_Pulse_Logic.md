# Simple_Pulse_Logic
(*****This is a very Simple Pulse) ( One Scan Bit ) or (RisingEdgeTrigger*****)


Var


Input : Array[1..2] of bool;


Pulse : bool;

end Var

IF Input[1] and not Input[2] then


	Pulse := true;
	Input[2] := true;
end_if

If not Input[1] then


	Input[2] := false;
end_if
