Problem_01:
int c = 0;
for(int i = n; i > 0; i /= 2) {
c++;
}
Ans : O(logn)



Problem_02:
int c = 0;
for(int i = n; i > 1; i /= i) {
c++;
}
Ans : O(1)


Problem_03:
int c = 0;
for(int i = 0; i < n; i += k) {
c++;
}
Ans : O(n)

Problem_04:
int c = 0;
for(int i = 1; i < n; i *= 2) {
c++;
}
Ans : O(logn)


Problem_05:
int c = 0;
for(int i = 0; i < n; i++) {
i*=k;
}
Ans : O(logn)


Problem_06:
int c = 0;
for(int i = 0; i < n; i++) {
  c++;
}
Ans : O(n)


Problem_07:
int c = 0;
for(int i = 0; i < n; i++) {
   for(int j=0;j<i;j++){

  c++;
}
}
Ans : O(n^2)


