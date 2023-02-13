# Daire-Diliminin-Alanı

double r, a;
double pi = 3.14;
double alan;

Scanner scanner = new Scanner(System.in);

System.out.println("Yarıçap giriniz: ");
r = scanner.nextDouble();

System.out.println("Açı giriniz: ");
a = scanner.nextDouble();

alan = pi * r * r * a / 360;
