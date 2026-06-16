# Simple_Pulse_Logic
(*****This is a very Simple Pulse) ( One Scan Bit ) or (RisingEdgeTrigger*****)


Var


Bool : Array[1..2] of bool;


end Var

IF Bool[1] and not Bool[2] then


	Pulse := true;
	bool[2] := false;
end_if

If not Bool[1] then


	bool[2] := false;
end_if
