# Function: <code>__ip_rt_update_pmtu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817550f0)
Location: net/ipv4/route.c:967
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_rt_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
```
**Symbols:**

```
ffffffff817550f0-ffffffff8175526d: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c1270)
Location: net/ipv4/route.c:973
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff817c1270-ffffffff817c13f1: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f0870)
Location: net/ipv4/route.c:979
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff817f0870-ffffffff817f09ee: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81810cc0)
Location: net/ipv4/route.c:997
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81810cc0-ffffffff81810e37: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818902a0)
Location: net/ipv4/route.c:1004
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff818902a0-ffffffff8189041e: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e3a10)
Location: net/ipv4/route.c:1001
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff818e3a10-ffffffff818e3bb0: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819108c0)
Location: net/ipv4/route.c:1004
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff819108c0-ffffffff81910a83: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81972b10)
Location: net/ipv4/route.c:1013
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81972b10-ffffffff81972cc2: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819a9480)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff819a9480-ffffffff819a9635: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a931b0)
Location: net/ipv4/route.c:1015
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a931b0-ffffffff81a93375: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9d040)
Location: net/ipv4/route.c:1015
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a9d040-ffffffff81a9d1ff: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a88260)
Location: net/ipv4/route.c:999
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81a88260-ffffffff81a88419: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b439f0-ffffffff81b43c1b: __ip_rt_update_pmtu (STB_LOCAL)
ffffffff81d39e55-ffffffff81d39e6a: __ip_rt_update_pmtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1021
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81cd04e0-ffffffff81cd071b: __ip_rt_update_pmtu (STB_LOCAL)
ffffffff81f06597-ffffffff81f065b2: __ip_rt_update_pmtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1021
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81e90690-ffffffff81e908cb: __ip_rt_update_pmtu (STB_LOCAL)
ffffffff820ae12c-ffffffff820ae147: __ip_rt_update_pmtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1021
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81eeee20-ffffffff81eef05e: __ip_rt_update_pmtu (STB_LOCAL)
ffffffff8212f62a-ffffffff8212f645: __ip_rt_update_pmtu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:1021
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81fb2f80-ffffffff81fb31bb: __ip_rt_update_pmtu (STB_LOCAL)
ffffffff822113e7-ffffffff82211402: __ip_rt_update_pmtu.cold (STB_LOCAL)
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
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c58e78)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffff800010c58e78-ffff800010c59038: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d68bc8)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:__ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
c0d68bc8-c0d68d84: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5acc0)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
c000000000d5acc0-c000000000d5af00: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c2e62)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffe0007c2e62-ffffffe0007c2f94: __ip_rt_update_pmtu (STB_LOCAL)
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
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819492f0)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff819492f0-ffffffff819494a5: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81902de0)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff81902de0-ffffffff81902f95: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b3ac0)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff819b3ac0-ffffffff819b3c75: __ip_rt_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __ip_rt_update_pmtu(struct rtable *rt, struct flowi4 *fl4, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bd190)
Location: net/ipv4/route.c:1014
Inline: False
Direct callers:
  - net/ipv4/route.c:ipv4_sk_update_pmtu
  - net/ipv4/route.c:ipv4_update_pmtu
  - net/ipv4/route.c:ip_rt_update_pmtu
```
**Symbols:**

```
ffffffff819bd190-ffffffff819bd35f: __ip_rt_update_pmtu (STB_LOCAL)
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
