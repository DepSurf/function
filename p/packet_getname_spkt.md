# Function: <code>packet_getname_spkt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int *uaddr_len, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81803240)
Location: net/packet/af_packet.c:3307
Inline: False
```
**Symbols:**

```
ffffffff81803240-ffffffff818032af: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int *uaddr_len, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818745d0)
Location: net/packet/af_packet.c:3380
Inline: False
```
**Symbols:**

```
ffffffff818745d0-ffffffff8187463f: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int *uaddr_len, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818a8bc0)
Location: net/packet/af_packet.c:3345
Inline: False
```
**Symbols:**

```
ffffffff818a8bc0-ffffffff818a8c2f: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int *uaddr_len, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818cf410)
Location: net/packet/af_packet.c:3411
Inline: False
```
**Symbols:**

```
ffffffff818cf410-ffffffff818cf47f: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int *uaddr_len, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81954380)
Location: net/packet/af_packet.c:3410
Inline: False
```
**Symbols:**

```
ffffffff81954380-ffffffff819543ef: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819ad920)
Location: net/packet/af_packet.c:3390
Inline: False
```
**Symbols:**

```
ffffffff819ad920-ffffffff819ad98d: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e4290)
Location: net/packet/af_packet.c:3402
Inline: False
```
**Symbols:**

```
ffffffff819e4290-ffffffff819e42fd: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a53270)
Location: net/packet/af_packet.c:3437
Inline: False
```
**Symbols:**

```
ffffffff81a53270-ffffffff81a532db: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a89e60)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
ffffffff81a89e60-ffffffff81a89ecb: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b85300)
Location: net/packet/af_packet.c:3467
Inline: False
```
**Symbols:**

```
ffffffff81b85300-ffffffff81b8536d: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3484
Inline: False
```
**Symbols:**

```
ffffffff81b94c50-ffffffff81b94d6e: packet_getname_spkt (STB_LOCAL)
ffffffff81c3319e-ffffffff81c331b6: packet_getname_spkt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3496
Inline: False
```
**Symbols:**

```
ffffffff81b83cc0-ffffffff81b83ddd: packet_getname_spkt (STB_LOCAL)
ffffffff81c254a2-ffffffff81c254ba: packet_getname_spkt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3500
Inline: False
```
**Symbols:**

```
ffffffff81c4fdb0-ffffffff81c4fecd: packet_getname_spkt (STB_LOCAL)
ffffffff81d418c0-ffffffff81d418d8: packet_getname_spkt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3554
Inline: False
```
**Symbols:**

```
ffffffff81df09c0-ffffffff81df0aea: packet_getname_spkt (STB_LOCAL)
ffffffff81f0e22d-ffffffff81f0e245: packet_getname_spkt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc4bc0)
Location: net/packet/af_packet.c:3553
Inline: False
```
**Symbols:**

```
ffffffff81fc4bc0-ffffffff81fc4c66: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff82025ab0)
Location: net/packet/af_packet.c:3566
Inline: False
```
**Symbols:**

```
ffffffff82025ab0-ffffffff82025b56: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f5420)
Location: net/packet/af_packet.c:3562
Inline: False
```
**Symbols:**

```
ffffffff820f5420-ffffffff820f54ce: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d56e60)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
ffff800010d56e60-ffff800010d56ee0: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e574e8)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
c0e574e8-c0e57554: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e901e0)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
c000000000e901e0-c000000000e90278: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe00088e67e)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
ffffffe00088e67e-ffffffe00088e718: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a294f0)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
ffffffff81a294f0-ffffffff81a2955b: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e66e0)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
ffffffff819e66e0-ffffffff819e674b: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a950a0)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
ffffffff81a950a0-ffffffff81a9510b: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int packet_getname_spkt(struct socket *sock, struct sockaddr *uaddr, int peer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa1450)
Location: net/packet/af_packet.c:3456
Inline: False
```
**Symbols:**

```
ffffffff81aa1450-ffffffff81aa14c4: packet_getname_spkt (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int *uaddr_len</code>
</li>
<li>
<b>Param reordered. </b>
<code>sock, uaddr, uaddr_len, peer</code> ➡️ <code>sock, uaddr, peer</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
