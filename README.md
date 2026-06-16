# Simple_Pulse_Logic
(*****(This is a very Simple Pulse) ( One Scan Bit ) or (RisingEdgeTrigger)*****)

IF Bool[1] and not Bool[2] then
	Pulse := true;
	bool[2] := false;
end_if

If not Bool[1] then
	bool[2] := false;
end_if
