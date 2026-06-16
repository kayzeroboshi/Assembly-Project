Given the following C program and the mapping of registers to variables, complete the MIPS implementation of procedure Sum.

int Dif(int a, int b) {
   return b - a;
}

int Sum(int m, int n) {
   int p = Dif(n+1, m-1);
   int q = Dif(m+1, n-1);
   return p + q;
}

int main() {
   int x, y;
   z = x + y + Sum(x, y);
   return 0;
}

---------------------------------------------------------------------------------------------------
<img width="198" height="197" alt="image" src="https://github.com/user-attachments/assets/593838c4-4a42-423c-86ba-cbd29befc27a" />

Hints: Use stack memory as needed. Use $a0, $a1 as arguments and $v0 as return value, according to the convention for procedure calling.

Ex: If the values of $s0 and $s1 are initialized in the simulator as:

<img width="161" height="146" alt="image" src="https://github.com/user-attachments/assets/cda1ec76-2ed0-4be6-8e75-8dc032d7b551" />

the result is stored in $s2:

<img width="161" height="196" alt="image" src="https://github.com/user-attachments/assets/45da6b50-ca18-4e38-875d-53aef932bf0e" />


Registers	Data
$s0	5
$s1	10
$s2	11
Note: Use the '+' button under the Registers display to initialize register values for $s0 and $s1.
