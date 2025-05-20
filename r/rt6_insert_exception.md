# Function: <code>rt6_insert_exception</code>

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
int rt6_insert_exception(struct rt6_info *nrt, struct rt6_info *ort);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191c090)
Location: net/ipv6/route.c:1269
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff8191c090-ffffffff8191c2fd: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, struct fib6_info *ort);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81973a30)
Location: net/ipv6/route.c:1412
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81973a30-ffffffff81973cab: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, struct fib6_info *ort);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9650)
Location: net/ipv6/route.c:1426
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff819a9650-ffffffff819a98af: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a16c00)
Location: net/ipv6/route.c:1630
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81a16c00-ffffffff81a16e80: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4d840)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81a4d840-ffffffff81a4dac1: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43b80)
Location: net/ipv6/route.c:1658
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b43b80-ffffffff81b43de2: rt6_insert_exception.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b52260)
Location: net/ipv6/route.c:1641
Inline: True
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b52260-ffffffff81b524e1: rt6_insert_exception.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3fc10)
Location: net/ipv6/route.c:1651
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b3fc10-ffffffff81b3fe8f: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c05e20)
Location: net/ipv6/route.c:1651
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81c05e20-ffffffff81c060a1: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da04e0)
Location: net/ipv6/route.c:1651
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81da04e0-ffffffff81da0779: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6f750)
Location: net/ipv6/route.c:1651
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81f6f750-ffffffff81f6f9e9: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcf830)
Location: net/ipv6/route.c:1650
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81fcf830-ffffffff81fcfaca: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209d090)
Location: net/ipv6/route.c:1652
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff8209d090-ffffffff8209d359: rt6_insert_exception (STB_LOCAL)
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
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d120b8)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffff800010d120b8-ffff800010d1240c: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e17df0)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
c0e17df0-c0e18094: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3e270)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
c000000000e3e270-c000000000e3e5d0: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe00085858a)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffe00085858a-ffffffe000858796: rt6_insert_exception (STB_LOCAL)
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
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eced0)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff819eced0-ffffffff819ed151: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9c90)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff819a9c90-ffffffff819a9f11: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a57950)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81a57950-ffffffff81a57bd1: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt6_insert_exception(struct rt6_info *nrt, const struct fib6_result *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a63a30)
Location: net/ipv6/route.c:1636
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_do_redirect
```
**Symbols:**

```
ffffffff81a63a30-ffffffff81a63cde: rt6_insert_exception (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct rt6_info *ort</code> ➡️ <code>struct fib6_info *ort</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct fib6_result *res</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib6_info *ort</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
