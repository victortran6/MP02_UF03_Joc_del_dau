# mElsQuedo by vtran

La funció agafarà tots aquells valors en els que el dau tregui un número major de 3.

```
Create function @mElsQuedo (@jugador as int, @dau as int)
returns integer
	declare @mElsQuedo int;

	if @dau BETWEEN 0 and 4
	begin
		set @mElsQuedo = 0
	end;

else
	begin
		set @mElsQuedo = 1
	end;
```
