given.rb
========
fambam = { 	uncles: ["huy", "johnny", "anh"], 
						sis: ["vy", "vivan"], 
						bros: ["viet", "vu", "vinhson"],
						aunts: ["nancy", "allie", "hanh"]
}

	fambam_level_1 = fambam.select do  |k,v| 
		k == :sis || k == :bros
	end
p fambam_level_1.values.flatten
