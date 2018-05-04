#Eric

La meva estrategia serà quedar-me el número si és 4 o més gran, si no li donaré el número a l'altre.

```

create function melsquedo(@jugador as int, @punts as int)
returns bit
as begin
	declare @quedat as bit;
	if @punts>=4
		set @quedat=1;
	else
		set @quedat=0;
	return @quedat
end

```
