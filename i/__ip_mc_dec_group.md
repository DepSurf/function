# Function: <code>__ip_mc_dec_group</code>

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
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c1d20)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff819c1d20-ffffffff819c1e29: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f88c0)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff819f88c0-ffffffff819f89c9: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae7cf0)
Location: net/ipv4/igmp.c:1659
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81ae7cf0-ffffffff81ae7df2: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af4bd0)
Location: net/ipv4/igmp.c:1659
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81af4bd0-ffffffff81af4cd2: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae0b80)
Location: net/ipv4/igmp.c:1666
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81ae0b80-ffffffff81ae0c82: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1666
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81d3c57b-ffffffff81d3c590: __ip_mc_dec_group.cold (STB_LOCAL)
ffffffff81ba0200-ffffffff81ba0311: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1673
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81f08dad-ffffffff81f08dc1: __ip_mc_dec_group.cold (STB_LOCAL)
ffffffff81d326b0-ffffffff81d327cc: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1673
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff820b06fe-ffffffff820b0712: __ip_mc_dec_group.cold (STB_LOCAL)
ffffffff81efa670-ffffffff81efa78c: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1674
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff8213197f-ffffffff82131993: __ip_mc_dec_group.cold (STB_LOCAL)
ffffffff81f5a110-ffffffff81f5a22c: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1676
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff8221333d-ffffffff82213351: __ip_mc_dec_group.cold (STB_LOCAL)
ffffffff82020650-ffffffff8202076c: __ip_mc_dec_group (STB_GLOBAL)
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
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cb1458)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffff800010cb1458-ffff800010cb15a0: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbc14c)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
c0dbc14c-c0dbc2a0: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc81e0)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
c000000000dc81e0-c000000000dc8390: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe000809500)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffe000809500-ffffffe000809612: __ip_mc_dec_group (STB_GLOBAL)
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
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81998660)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81998660-ffffffff81998769: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81952120)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81952120-ffffffff81952229: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a02f00)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81a02f00-ffffffff81a03009: __ip_mc_dec_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __ip_mc_dec_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0d430)
Location: net/ipv4/igmp.c:1661
Inline: False
Direct callers:
  - net/ipv4/igmp.c:ip_mc_drop_socket
  - net/ipv4/igmp.c:ip_mc_leave_group
  - net/ipv4/igmp.c:ip_mc_down
```
**Symbols:**

```
ffffffff81a0d430-ffffffff81a0d539: __ip_mc_dec_group (STB_GLOBAL)
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
