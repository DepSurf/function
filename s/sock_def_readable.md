# Function: <code>sock_def_readable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81701930)
Location: net/core/sock.c:2301
Inline: True
```
**Symbols:**

```
ffffffff81701930-ffffffff8170198e: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81768bc0)
Location: net/core/sock.c:2374
Inline: True
```
**Symbols:**

```
ffffffff81768bc0-ffffffff81768c21: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81795ad0)
Location: net/core/sock.c:2398
Inline: True
```
**Symbols:**

```
ffffffff81795ad0-ffffffff81795b31: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b3d30)
Location: net/core/sock.c:2558
Inline: True
```
**Symbols:**

```
ffffffff817b3d30-ffffffff817b3d91: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182bf70)
Location: net/core/sock.c:2617
Inline: True
```
**Symbols:**

```
ffffffff8182bf70-ffffffff8182bfd4: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81876150)
Location: net/core/sock.c:2692
Inline: True
```
**Symbols:**

```
ffffffff81876150-ffffffff818761b7: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818969d0)
Location: net/core/sock.c:2636
Inline: True
```
**Symbols:**

```
ffffffff818969d0-ffffffff81896a37: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818e1520)
Location: net/core/sock.c:2779
Inline: False
```
**Symbols:**

```
ffffffff818e1520-ffffffff818e1587: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819136e0)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
ffffffff819136e0-ffffffff81913747: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e5020)
Location: net/core/sock.c:2923
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff819e5020-ffffffff819e5088: sock_def_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e48f0)
Location: net/core/sock.c:2895
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff819e48f0-ffffffff819e4967: sock_def_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819ca970)
Location: net/core/sock.c:2918
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff819ca970-ffffffff819ca9e7: sock_def_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a79fa0)
Location: net/core/sock.c:3049
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81a79fa0-ffffffff81a7a017: sock_def_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bedbd0)
Location: net/core/sock.c:3212
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81bedbd0-ffffffff81bedc69: sock_def_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9a9f0)
Location: net/core/sock.c:3292
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81d9a9f0-ffffffff81d9aa89: sock_def_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e094b0)
Location: net/core/sock.c:3323
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81e094b0-ffffffff81e09594: sock_def_readable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec5ea0)
Location: net/core/sock.c:3333
Inline: False
Direct callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
  - net/xdp/xsk.c:__xsk_map_flush
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81ec5ea0-ffffffff81ec5f84: sock_def_readable (STB_GLOBAL)
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
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010baa9f8)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
ffff800010baa9f8-ffff800010baaa70: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc9a94)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
c0cc9a94-c0cc9b00: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c81780)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
c000000000c81780-c000000000c81830: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073e862)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
ffffffe00073e862-ffffffe00073e8ca: sock_def_readable (STB_LOCAL)
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
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b36e0)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
ffffffff818b36e0-ffffffff818b3747: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186d630)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
ffffffff8186d630-ffffffff8186d697: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819046e0)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
ffffffff819046e0-ffffffff81904747: sock_def_readable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_def_readable(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81925770)
Location: net/core/sock.c:2794
Inline: False
```
**Symbols:**

```
ffffffff81925770-ffffffff819257f0: sock_def_readable (STB_LOCAL)
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
