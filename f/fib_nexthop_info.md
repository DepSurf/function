# Function: <code>fib_nexthop_info</code>

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
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c7380)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819c7380-ffffffff819c754d: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819fdf30)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff819fdf30-ffffffff819fe0fd: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aeca40)
Location: net/ipv4/fib_semantics.c:1593
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81aeca40-ffffffff81aecc14: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af9df0)
Location: net/ipv4/fib_semantics.c:1593
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81af9df0-ffffffff81af9fe5: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae5530)
Location: net/ipv4/fib_semantics.c:1594
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81ae5530-ffffffff81ae5725: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba4930)
Location: net/ipv4/fib_semantics.c:1636
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81ba4930-ffffffff81ba4b25: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81d372b0)
Location: net/ipv4/fib_semantics.c:1623
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81d372b0-ffffffff81d374aa: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81effad0)
Location: net/ipv4/fib_semantics.c:1629
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81effad0-ffffffff81effcca: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f5f550)
Location: net/ipv4/fib_semantics.c:1629
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81f5f550-ffffffff81f5f74a: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff82025b20)
Location: net/ipv4/fib_semantics.c:1636
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff82025b20-ffffffff82025d1a: fib_nexthop_info (STB_GLOBAL)
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
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb6090)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffff800010cb6090-ffff800010cb6270: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc1b6c)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c0dc1b6c-c0dc1d7c: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dcdf90)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
c000000000dcdf90-c000000000dce200: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080d888)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffe00080d888-ffffffe00080da0a: fib_nexthop_info (STB_GLOBAL)
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
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199dcd0)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff8199dcd0-ffffffff8199de9d: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81957790)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81957790-ffffffff8195795d: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a08570)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a08570-ffffffff81a0873d: fib_nexthop_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fib_nexthop_info(struct sk_buff *skb, const struct fib_nh_common *nhc, u8 rt_family, unsigned char *flags, bool skip_oif);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a12cc0)
Location: net/ipv4/fib_semantics.c:1584
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_dump_info
  - net/ipv4/fib_semantics.c:fib_add_nexthop
  - net/ipv6/route.c:rt6_fill_node
```
**Symbols:**

```
ffffffff81a12cc0-ffffffff81a12e99: fib_nexthop_info (STB_GLOBAL)
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
