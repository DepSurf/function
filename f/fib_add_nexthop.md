# Function: <code>fib_add_nexthop</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c7550)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819c7550-ffffffff819c7619: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819fe100)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819fe100-ffffffff819fe1c9: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aecc20)
Location: net/ipv4/fib_semantics.c:1665
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81aecc20-ffffffff81aecce9: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af9ff0)
Location: net/ipv4/fib_semantics.c:1664
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv4/fib_semantics.c:fib_add_multipath
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81af9ff0-ffffffff81afa0b9: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae5730)
Location: net/ipv4/fib_semantics.c:1665
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81ae5730-ffffffff81ae57f9: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family, u32 nh_tclassid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba4b30)
Location: net/ipv4/fib_semantics.c:1707
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81ba4b30-ffffffff81ba4c2a: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family, u32 nh_tclassid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81d374b0)
Location: net/ipv4/fib_semantics.c:1694
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81d374b0-ffffffff81d375b9: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family, u32 nh_tclassid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81effce0)
Location: net/ipv4/fib_semantics.c:1700
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81effce0-ffffffff81effde9: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family, u32 nh_tclassid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f5f760)
Location: net/ipv4/fib_semantics.c:1700
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81f5f760-ffffffff81f5f869: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family, u32 nh_tclassid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff82025d30)
Location: net/ipv4/fib_semantics.c:1707
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff82025d30-ffffffff82025e39: fib_add_nexthop (STB_GLOBAL)
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
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb6270)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffff800010cb6270-ffff800010cb6358: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc1d7c)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c0dc1d7c-c0dc1e50: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dce200)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c000000000dce200-c000000000dce320: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080da0a)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffe00080da0a-ffffffe00080daa6: fib_add_nexthop (STB_GLOBAL)
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
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199dea0)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8199dea0-ffffffff8199df69: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81957960)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81957960-ffffffff81957a29: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a08740)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a08740-ffffffff81a08809: fib_add_nexthop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_add_nexthop(struct sk_buff *skb, const struct fib_nh_common *nhc, int nh_weight, u8 rt_family);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a12ea0)
Location: net/ipv4/fib_semantics.c:1656
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a12ea0-ffffffff81a12f69: fib_add_nexthop (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 nh_tclassid</code>
</li>
</ul>
</details>
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
