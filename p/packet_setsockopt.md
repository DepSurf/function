# Function: <code>packet_setsockopt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81805cd0)
Location: net/packet/af_packet.c:3506
Inline: False
```
**Symbols:**

```
ffffffff81805cd0-ffffffff81806832: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81876730)
Location: net/packet/af_packet.c:3580
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81876730-ffffffff818773a6: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818ab700)
Location: net/packet/af_packet.c:3545
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff818ab700-ffffffff818ac38a: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff818d1760)
Location: net/packet/af_packet.c:3611
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff818d1760-ffffffff818d24a1: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81956660)
Location: net/packet/af_packet.c:3610
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81956660-ffffffff819573c3: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3588
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff819b3150-ffffffff819b3e9e: packet_setsockopt (STB_LOCAL)
ffffffff819b3ffe-ffffffff819b4016: packet_setsockopt.cold.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3600
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff819ea0a0-ffffffff819eaecb: packet_setsockopt (STB_LOCAL)
ffffffff819eb030-ffffffff819eb048: packet_setsockopt.cold.86 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3635
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81a59200-ffffffff81a5a02c: packet_setsockopt (STB_LOCAL)
ffffffff81a5a1f3-ffffffff81a5a20b: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3654
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81a8f310-ffffffff81a9013c: packet_setsockopt (STB_LOCAL)
ffffffff81a90e0a-ffffffff81a90e22: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffff81b8a630)
Location: net/packet/af_packet.c:3665
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81b8a630-ffffffff81b8ae1b: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3682
Inline: False
```
**Symbols:**

```
ffffffff81b9b630-ffffffff81b9bf1c: packet_setsockopt (STB_LOCAL)
ffffffff81c332b9-ffffffff81c332c5: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3696
Inline: False
```
**Symbols:**

```
ffffffff81b89ae0-ffffffff81b8a5c5: packet_setsockopt (STB_LOCAL)
ffffffff81c2558d-ffffffff81c255a5: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3700
Inline: False
```
**Symbols:**

```
ffffffff81c55bf0-ffffffff81c566dc: packet_setsockopt (STB_LOCAL)
ffffffff81d41a30-ffffffff81d41a48: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3754
Inline: False
```
**Symbols:**

```
ffffffff81df7bf0-ffffffff81df87db: packet_setsockopt (STB_LOCAL)
ffffffff81f0e3c6-ffffffff81f0e3d2: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3753
Inline: False
```
**Symbols:**

```
ffffffff81fcc220-ffffffff81fcccdc: packet_setsockopt (STB_LOCAL)
ffffffff820b544c-ffffffff820b5461: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3766
Inline: False
```
**Symbols:**

```
ffffffff8202d500-ffffffff8202dfcf: packet_setsockopt (STB_LOCAL)
ffffffff82136347-ffffffff8213635c: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3767
Inline: False
```
**Symbols:**

```
ffffffff820fcf80-ffffffff820fda4f: packet_setsockopt (STB_LOCAL)
ffffffff82217f34-ffffffff82217f49: packet_setsockopt.cold (STB_LOCAL)
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
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffff800010d5c548)
Location: net/packet/af_packet.c:3654
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffff800010d5c548-ffff800010d5d1c8: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c0e5d590)
Location: net/packet/af_packet.c:3654
Inline: False
```
**Symbols:**

```
c0e5d590-c0e5e5a0: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (c000000000e98060)
Location: net/packet/af_packet.c:3654
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
c000000000e98060-c000000000e99090: packet_setsockopt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/packet/af_packet.c (ffffffe000892dc8)
Location: net/packet/af_packet.c:3654
Inline: False
```
**Symbols:**

```
ffffffe000892dc8-ffffffe0008937ce: packet_setsockopt (STB_LOCAL)
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
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3654
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81a2e9a0-ffffffff81a2f7cc: packet_setsockopt (STB_LOCAL)
ffffffff81a3049a-ffffffff81a304b2: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3654
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff819ebb90-ffffffff819ec9bc: packet_setsockopt (STB_LOCAL)
ffffffff819ed68a-ffffffff819ed6a2: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3654
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81a9a550-ffffffff81a9b37c: packet_setsockopt (STB_LOCAL)
ffffffff81a9c04a-ffffffff81a9c062: packet_setsockopt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int packet_setsockopt(struct socket *sock, int level, int optname, char *optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/packet/af_packet.c (0)
Location: net/packet/af_packet.c:3654
Inline: False
Direct callers:
  - net/packet/af_packet.c:compat_packet_setsockopt
```
**Symbols:**

```
ffffffff81aa72a0-ffffffff81aa80ef: packet_setsockopt (STB_LOCAL)
ffffffff81aa8265-ffffffff81aa827d: packet_setsockopt.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *optval</code> ➡️ <code>sockptr_t optval</code>
</li>
</ul>
</details>
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
