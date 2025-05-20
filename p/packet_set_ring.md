# Function: <code>packet_set_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818050c0)
Location: net/packet/af_packet.c:4061
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff818050c0-ffffffff81805807: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81875c20)
Location: net/packet/af_packet.c:4154
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81875c20-ffffffff818763c9: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818aa100)
Location: net/packet/af_packet.c:4127
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff818aa100-ffffffff818aa8c7: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d0c80)
Location: net/packet/af_packet.c:4200
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff818d0c80-ffffffff818d13d1: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81955ba0)
Location: net/packet/af_packet.c:4199
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81955ba0-ffffffff819562f3: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4204
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff819b1000-ffffffff819b1722: packet_set_ring (STB_LOCAL)
ffffffff819b3fb8-ffffffff819b3fd3: packet_set_ring.cold.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4233
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff819e83f0-ffffffff819e8b0b: packet_set_ring (STB_LOCAL)
ffffffff819eafea-ffffffff819eb005: packet_set_ring.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4266
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a586e0-ffffffff81a58e78: packet_set_ring (STB_LOCAL)
ffffffff81a5a1b8-ffffffff81a5a1e0: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a8e7c0-ffffffff81a8ef87: packet_set_ring (STB_LOCAL)
ffffffff81a90def-ffffffff81a90e0a: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4296
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81b89940-ffffffff81b89dda: packet_set_ring (STB_LOCAL)
ffffffff81b8c288-ffffffff81b8c2a2: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4292
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81b99450-ffffffff81b998f5: packet_set_ring (STB_LOCAL)
ffffffff81c33279-ffffffff81c33293: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4306
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81b88860-ffffffff81b88e19: packet_set_ring (STB_LOCAL)
ffffffff81c25573-ffffffff81c2558d: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4307
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81c54960-ffffffff81c54f26: packet_set_ring (STB_LOCAL)
ffffffff81d41a16-ffffffff81d41a30: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4362
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81df4b40-ffffffff81df5122: packet_set_ring (STB_LOCAL)
ffffffff81f0e2d2-ffffffff81f0e2ea: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc7510)
Location: net/packet/af_packet.c:4361
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81fc7510-ffffffff81fc7a9f: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820284b0)
Location: net/packet/af_packet.c:4382
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff820284b0-ffffffff82028a2c: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f7ee0)
Location: net/packet/af_packet.c:4383
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff820f7ee0-ffffffff820f8464: packet_set_ring (STB_LOCAL)
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
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d5b9e0)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffff800010d5b9e0-ffff800010d5c1b0: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e5bae8)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
c0e5bae8-c0e5c1c4: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e97320)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
c000000000e97320-c000000000e97bd8: packet_set_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe000891d6c)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffe000891d6c-ffffffe00089238e: packet_set_ring (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a2de50-ffffffff81a2e617: packet_set_ring (STB_LOCAL)
ffffffff81a3047f-ffffffff81a3049a: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff819eb040-ffffffff819eb807: packet_set_ring (STB_LOCAL)
ffffffff819ed66f-ffffffff819ed68a: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81a99a00-ffffffff81a9a1c7: packet_set_ring (STB_LOCAL)
ffffffff81a9c02f-ffffffff81a9c04a: packet_set_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int packet_set_ring(struct sock *sk, union tpacket_req_u *req_u, int closing, int tx_ring);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:4285
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_setsockopt
  - net/packet/af_packet.c:packet_release
  - net/packet/af_packet.c:packet_release
```
**Symbols:**

```
ffffffff81aa6730-ffffffff81aa6ef6: packet_set_ring (STB_LOCAL)
ffffffff81aa824a-ffffffff81aa8265: packet_set_ring.cold (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
