# Function: <code>__raw_v4_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81784110)
Location: net/ipv4/raw.c:121
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81784110-ffffffff81784160: __raw_v4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff817f16a0)
Location: net/ipv4/raw.c:123
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff817f16a0-ffffffff817f16f6: __raw_v4_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81822430)
Location: net/ipv4/raw.c:124
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81822430-ffffffff81822486: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818430a0)
Location: net/ipv4/raw.c:124
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff818430a0-ffffffff818430f6: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818c2a10)
Location: net/ipv4/raw.c:124
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff818c2a10-ffffffff818c2ab8: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819186a0)
Location: net/ipv4/raw.c:124
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff819186a0-ffffffff81918748: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81946e20)
Location: net/ipv4/raw.c:124
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81946e20-ffffffff81946ef3: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819ab4a0)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff819ab4a0-ffffffff819ab573: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819e2170)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff819e2170-ffffffff819e2243: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81acf800)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_v4_input
```
**Symbols:**

```
ffffffff81acf800-ffffffff81acf8d2: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81adb820)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_v4_input
```
**Symbols:**

```
ffffffff81adb820-ffffffff81adb8f2: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81ac6870)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_v4_input
```
**Symbols:**

```
ffffffff81ac6870-ffffffff81ac693b: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81b85080)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_v4_input
  - net/ipv4/raw.c:raw_v4_input
```
**Symbols:**

```
ffffffff81b85080-ffffffff81b8514b: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffff800010c96140)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffff800010c96140-ffff800010c9623c: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (c0da4920)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
c0da4920-c0da49e4: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (c000000000da76a0)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
c000000000da76a0-c000000000da7788: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffe0007f5244)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffe0007f5244-ffffffe0007f52e8: __raw_v4_lookup (STB_GLOBAL)
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
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81981fe0)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff81981fe0-ffffffff819820b3: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff8193baa0)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff8193baa0-ffffffff8193bb73: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819ec7b0)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff819ec7b0-ffffffff819ec883: __raw_v4_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *__raw_v4_lookup(struct net *net, struct sock *sk, short unsigned int num, __be32 raddr, __be32 laddr, int dif, int sdif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff819f66a0)
Location: net/ipv4/raw.c:120
Inline: False
Direct callers:
  - net/ipv4/raw.c:raw_icmp_error
  - net/ipv4/raw.c:raw_local_deliver
  - net/ipv4/raw.c:raw_local_deliver
```
**Symbols:**

```
ffffffff819f66a0-ffffffff819f6773: __raw_v4_lookup (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sdif</code>
</li>
</ul>
</details>
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
