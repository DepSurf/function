# Function: <code>rt6_nh_nlmsg_size</code>

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
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a130c0)
Location: net/ipv6/route.c:5269
Inline: False
```
**Symbols:**

```
ffffffff81a130c0-ffffffff81a130ee: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49cb0)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
ffffffff81a49cb0-ffffffff81a49cde: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b407a0)
Location: net/ipv6/route.c:5363
Inline: False
```
**Symbols:**

```
ffffffff81b407a0-ffffffff81b407d1: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4f260)
Location: net/ipv6/route.c:5348
Inline: False
```
**Symbols:**

```
ffffffff81b4f260-ffffffff81b4f291: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3cf80)
Location: net/ipv6/route.c:5365
Inline: False
```
**Symbols:**

```
ffffffff81b3cf80-ffffffff81b3cfb1: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c03810)
Location: net/ipv6/route.c:5523
Inline: False
```
**Symbols:**

```
ffffffff81c03810-ffffffff81c03841: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9d840)
Location: net/ipv6/route.c:5516
Inline: False
```
**Symbols:**

```
ffffffff81d9d840-ffffffff81d9d885: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6ee0c)
Location: net/ipv6/route.c:5516
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
```
**Symbols:**

```
ffffffff81f6c760-ffffffff81f6c7a5: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcef1c)
Location: net/ipv6/route.c:5514
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
```
**Symbols:**

```
ffffffff81fcc8a0-ffffffff81fcc8e5: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209c77c)
Location: net/ipv6/route.c:5507
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_nlmsg_size
  - net/ipv6/route.c:rt6_nlmsg_size
```
**Symbols:**

```
ffffffff8209a080-ffffffff8209a0c5: rt6_nh_nlmsg_size (STB_LOCAL)
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
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0ce48)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
ffff800010d0ce48-ffff800010d0ce9c: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e13644)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
c0e13644-c0e13690: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e38690)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
c000000000e38690-c000000000e38708: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe0008547cc)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
ffffffe0008547cc-ffffffe000854812: rt6_nh_nlmsg_size (STB_LOCAL)
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
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e9340)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
ffffffff819e9340-ffffffff819e936e: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6100)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
ffffffff819a6100-ffffffff819a612e: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53dc0)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
ffffffff81a53dc0-ffffffff81a53dee: rt6_nh_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt6_nh_nlmsg_size(struct fib6_nh *nh, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5fdb0)
Location: net/ipv6/route.c:5283
Inline: False
```
**Symbols:**

```
ffffffff81a5fdb0-ffffffff81a5fdde: rt6_nh_nlmsg_size (STB_LOCAL)
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
