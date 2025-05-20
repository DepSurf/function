# Function: <code>lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81893560)
Location: net/ipv4/inetpeer.c:97
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81893560-ffffffff81893646: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff818e7790)
Location: net/ipv4/inetpeer.c:98
Inline: False
```
**Symbols:**

```
ffffffff818e7790-ffffffff818e787c: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81914640)
Location: net/ipv4/inetpeer.c:98
Inline: False
```
**Symbols:**

```
ffffffff81914640-ffffffff8191472c: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81976ba0)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81976ba0-ffffffff81976c63: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff819ad530)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff819ad530-ffffffff819ad5f3: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81a974c0)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81a974c0-ffffffff81a9758e: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81aa1480)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81aa1480-ffffffff81aa154e: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81a8c3d0)
Location: net/ipv4/inetpeer.c:91
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81a8c3d0-ffffffff81a8c49a: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81b473a0)
Location: net/ipv4/inetpeer.c:91
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81b473a0-ffffffff81b475dd: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81cd4510)
Location: net/ipv4/inetpeer.c:91
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81cd4510-ffffffff81cd47ab: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81e947e0)
Location: net/ipv4/inetpeer.c:91
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81e947e0-ffffffff81e94a7b: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81ef2fb0)
Location: net/ipv4/inetpeer.c:91
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81ef2fb0-ffffffff81ef3244: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81fb6f40)
Location: net/ipv4/inetpeer.c:91
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81fb6f40-ffffffff81fb71d4: lookup (STB_LOCAL)
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
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffff800010c5d718)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffff800010c5d718-ffff800010c5d84c: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (c0d6cc44)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
c0d6cc44-c0d6cd28: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (c000000000d5fce0)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
c000000000d5fce0-c000000000d5fe44: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffe0007c6132)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffe0007c6132-ffffffe0007c6236: lookup (STB_LOCAL)
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
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff8194d3a0)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff8194d3a0-ffffffff8194d463: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff81906e90)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff81906e90-ffffffff81906f53: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff819b7b70)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff819b7b70-ffffffff819b7c33: lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct inet_peer *lookup(const struct inetpeer_addr *daddr, struct inet_peer_base *base, unsigned int seq, struct inet_peer **gc_stack, unsigned int *gc_cnt, struct rb_node **parent_p, struct rb_node ***pp_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inetpeer.c (ffffffff819c13e0)
Location: net/ipv4/inetpeer.c:98
Inline: False
Direct callers:
  - net/ipv4/inetpeer.c:inet_getpeer
  - net/ipv4/inetpeer.c:inet_getpeer
```
**Symbols:**

```
ffffffff819c13e0-ffffffff819c14a3: lookup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
