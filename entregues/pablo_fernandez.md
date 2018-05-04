
# PROVA

```
create function dbo.mElsQuedo( @nJugador int, @punts int ) 
returns bit
as begin
	declare @quedarme as bit
	if @punts <=2
		set @quedarme=0
	else
		set @quedarme=1
	return @quedarme
end

```
