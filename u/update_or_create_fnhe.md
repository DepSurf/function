# Function: <code>update_or_create_fnhe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh *nh, __be32 daddr, __be32 gw, u32 pmtu, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81754680)
Location: net/ipv4/route.c:621
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_do_redirect
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81754680-ffffffff817549a2: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh *nh, __be32 daddr, __be32 gw, u32 pmtu, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c0810)
Location: net/ipv4/route.c:627
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff817c0810-ffffffff817c0b2c: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh *nh, __be32 daddr, __be32 gw, u32 pmtu, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817efce0)
Location: net/ipv4/route.c:630
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff817efce0-ffffffff817f0001: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh *nh, __be32 daddr, __be32 gw, u32 pmtu, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8180fda0)
Location: net/ipv4/route.c:648
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff8180fda0-ffffffff818100c0: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh *nh, __be32 daddr, __be32 gw, u32 pmtu, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188f460)
Location: net/ipv4/route.c:651
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff8188f460-ffffffff8188f78a: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh *nh, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e31c0)
Location: net/ipv4/route.c:635
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff818e31c0-ffffffff818e352b: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh *nh, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81910070)
Location: net/ipv4/route.c:635
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81910070-ffffffff819103db: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819724f0)
Location: net/ipv4/route.c:643
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff819724f0-ffffffff81972864: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819a8e60)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff819a8e60-ffffffff819a91df: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a92800)
Location: net/ipv4/route.c:644
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81a92800-ffffffff81a92bce: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9c6a0)
Location: net/ipv4/route.c:644
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81a9c6a0-ffffffff81a9ca67: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a87830)
Location: net/ipv4/route.c:627
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81a87830-ffffffff81a87b29: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:635
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81b41ca0-ffffffff81b42052: update_or_create_fnhe (STB_LOCAL)
ffffffff81d39ce1-ffffffff81d39d1b: update_or_create_fnhe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:638
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81cce680-ffffffff81ccea3c: update_or_create_fnhe (STB_LOCAL)
ffffffff81f06424-ffffffff81f0645e: update_or_create_fnhe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:638
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81e8e8b0-ffffffff81e8ec6b: update_or_create_fnhe (STB_LOCAL)
ffffffff820adffe-ffffffff820ae028: update_or_create_fnhe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:638
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81eecf90-ffffffff81eed363: update_or_create_fnhe (STB_LOCAL)
ffffffff8212f4fb-ffffffff8212f525: update_or_create_fnhe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:638
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81fb1020-ffffffff81fb1422: update_or_create_fnhe (STB_LOCAL)
ffffffff822112a0-ffffffff822112ca: update_or_create_fnhe.cold (STB_LOCAL)
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
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c587e0)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffff800010c587e0-ffff800010c58c10: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6858c)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
c0d6858c-c0d68944: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5a490)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
c000000000d5a490-c000000000d5a928: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c28d8)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffe0007c28d8-ffffffe0007c2c34: update_or_create_fnhe (STB_LOCAL)
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
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81948cd0)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff81948cd0-ffffffff8194904f: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819027c0)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff819027c0-ffffffff81902b3f: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b34a0)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff819b34a0-ffffffff819b381f: update_or_create_fnhe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void update_or_create_fnhe(struct fib_nh_common *nhc, __be32 daddr, __be32 gw, u32 pmtu, bool lock, long unsigned int expires);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bcb70)
Location: net/ipv4/route.c:645
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_rt_update_pmtu
  - net/ipv4/route.c:__ip_do_redirect
```
**Symbols:**

```
ffffffff819bcb70-ffffffff819bceef: update_or_create_fnhe (STB_LOCAL)
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
<b>Param added. </b>
<code>bool lock</code>
</li>
<li>
<b>Param reordered. </b>
<code>nh, daddr, gw, pmtu, expires</code> ➡️ <code>nh, daddr, gw, pmtu, lock, expires</code>
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
<code>struct fib_nh_common *nhc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib_nh *nh</code>
</li>
</ul>
</details>
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
