# Function: <code>rt6_do_update_pmtu</code>

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
In net/ipv6/route.c (ffffffff817d6ce0)
Location: net/ipv6/route.c:1325
Inline: True
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
In net/ipv6/route.c (ffffffff81845370)
Location: net/ipv6/route.c:1336
Inline: True
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
In net/ipv6/route.c (ffffffff81877136)
Location: net/ipv6/route.c:1344
Inline: True
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
In net/ipv6/route.c (ffffffff8189c3a1)
Location: net/ipv6/route.c:1375
Inline: True
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
In net/ipv6/route.c (ffffffff8191c3df)
Location: net/ipv6/route.c:2054
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819729f0)
Location: net/ipv6/route.c:2292
Inline: False
```
**Symbols:**

```
ffffffff819729f0-ffffffff81972aaf: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a85b0)
Location: net/ipv6/route.c:2283
Inline: False
```
**Symbols:**

```
ffffffff819a85b0-ffffffff819a866f: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a14f90)
Location: net/ipv6/route.c:2678
Inline: False
```
**Symbols:**

```
ffffffff81a14f90-ffffffff81a15051: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4bb80)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
ffffffff81a4bb80-ffffffff81a4bc41: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b421c0)
Location: net/ipv6/route.c:2706
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b421c0-ffffffff81b42281: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b50af0)
Location: net/ipv6/route.c:2689
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b50af0-ffffffff81b50bb8: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3ebf0)
Location: net/ipv6/route.c:2698
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81b3ebf0-ffffffff81b3ecb8: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04e70)
Location: net/ipv6/route.c:2828
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81c04e70-ffffffff81c04f38: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9f780)
Location: net/ipv6/route.c:2824
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81d9f780-ffffffff81d9f85d: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6e7f0)
Location: net/ipv6/route.c:2824
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81f6e7f0-ffffffff81f6e8cd: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fce8b0)
Location: net/ipv6/route.c:2823
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff81fce8b0-ffffffff81fce990: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209c110)
Location: net/ipv6/route.c:2825
Inline: False
Direct callers:
  - net/ipv6/route.c:__ip6_rt_update_pmtu
  - net/ipv6/route.c:__ip6_rt_update_pmtu
```
**Symbols:**

```
ffffffff8209c110-ffffffff8209c1f0: rt6_do_update_pmtu (STB_LOCAL)
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
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0e858)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
ffff800010d0e858-ffff800010d0e92c: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e15ba4)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
c0e15ba4-c0e15c68: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3b9a0)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
c000000000e3b9a0-c000000000e3bae4: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000856c2c)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
ffffffe000856c2c-ffffffe000856cce: rt6_do_update_pmtu (STB_LOCAL)
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
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819eb210)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
ffffffff819eb210-ffffffff819eb2d1: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a7fd0)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
ffffffff819a7fd0-ffffffff819a8091: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a55c90)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
ffffffff81a55c90-ffffffff81a55d51: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt6_do_update_pmtu(struct rt6_info *rt, u32 mtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a61c90)
Location: net/ipv6/route.c:2684
Inline: False
```
**Symbols:**

```
ffffffff81a61c90-ffffffff81a61d5f: rt6_do_update_pmtu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
