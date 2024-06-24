In the assignments solutions there are soe problems so please refer to this solution which is correct and verified from solution video..

Problem:01
for(int i = 0; i < n; i++) {
 for(int j = 0; j * j < n; j++) {
 cout << “PhysicsWallah ”;
 }
}

Ans: O(n * sqrt(n))

Problem:02
int c = 0;
for(int i = 0; i < n; i++) {
for(int j = 1; j < n; j *= 2) {
c++;
}
}

Ans:O(n log n)

Problem:03
int c = 0;
for(int i = 0; i < n; i++) {
for(int j = 1; j * j < n; j *= 2) {
c++;
}
}

Ans:O(n log n)

Problem:04
int c = 0;
for(int i = n; i > 0; i /= 2) {
for(int j = 0; j < i; j ++) {
c++;
}
}

Ans:O(n)

Problem:05
int c = 0;
for(int i = 1; i < n; i*=2) {
for(int j = n; j > i; j--) {
c++;
}
}

Ans:O(logN)