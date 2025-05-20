# Function: <code>packet_snd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81807f63)
Location: net/packet/af_packet.c:2634
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81879979)
Location: net/packet/af_packet.c:2804
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818ae059)
Location: net/packet/af_packet.c:2758
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d49f6)
Location: net/packet/af_packet.c:2826
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81959466)
Location: net/packet/af_packet.c:2815
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819b0203)
Location: net/packet/af_packet.c:2789
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e79fc)
Location: net/packet/af_packet.c:2796
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a54560)
Location: net/packet/af_packet.c:2820
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81a54560-ffffffff81a54efe: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a8b150)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81a8b150-ffffffff81a8baee: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b86f40)
Location: net/packet/af_packet.c:2850
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81b86f40-ffffffff81b876ab: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b96aa0)
Location: net/packet/af_packet.c:2867
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81b96aa0-ffffffff81b971e3: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b85aa0)
Location: net/packet/af_packet.c:2876
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81b85aa0-ffffffff81b861e3: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81c51e40)
Location: net/packet/af_packet.c:2882
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81c51e40-ffffffff81c525a1: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81df3ea0)
Location: net/packet/af_packet.c:2934
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81df3ea0-ffffffff81df4650: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81fc8c50)
Location: net/packet/af_packet.c:2934
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81fc8c50-ffffffff81fc93f9: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820295b0)
Location: net/packet/af_packet.c:2947
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff820295b0-ffffffff82029d6c: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff820f9070)
Location: net/packet/af_packet.c:2943
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff820f9070-ffffffff820f983f: packet_snd (STB_LOCAL)
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
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d59cd0)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffff800010d59cd0-ffff800010d5a528: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e586dc)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
c0e586dc-c0e58fc0: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e93eb0)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
c000000000e93eb0-c000000000e949cc: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe00088fbea)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffe00088fbea-ffffffe000890334: packet_snd (STB_LOCAL)
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
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a2a7e0)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81a2a7e0-ffffffff81a2b17e: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff819e79d0)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff819e79d0-ffffffff819e836e: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81a96390)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81a96390-ffffffff81a96d2e: packet_snd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int packet_snd(struct socket *sock, struct msghdr *msg, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81aa3000)
Location: net/packet/af_packet.c:2839
Inline: False
Direct callers:
  - net/packet/af_packet.c:packet_sendmsg
```
**Symbols:**

```
ffffffff81aa3000-ffffffff81aa39a8: packet_snd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
