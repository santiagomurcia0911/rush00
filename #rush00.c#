#include<unistd.h>

void	ft_putchar(char c);

void	rush(int x, int y)
{
	int	h;
	int	v;

	v = 1;
	while (v <= y && x > 0)
	{
		h = 1;
		while (h <= x)
		{
			if ((h == 1 && v == 1) || (h == x && v == y && h != 1 && v != 1))
				ft_putchar('A');
			else if ((h == x && v == 1) || (h == 1 && v == y))
				ft_putchar('C');
			else if ((h == 1) || (h == x) || (v == 1) || (v == y))
				ft_putchar('B');
			else
				ft_putchar(' ');
			h++;
		}
		ft_putchar('\n');
		v++;
	}
}
