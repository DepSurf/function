# Function: <code>____ip_mc_inc_group</code>

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
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c2df0)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff819c2df0-ffffffff819c2fdf: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819f9990)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff819f9990-ffffffff819f9b7f: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae7700)
Location: net/ipv4/igmp.c:1420
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81ae7700-ffffffff81ae7936: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af45e0)
Location: net/ipv4/igmp.c:1420
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81af45e0-ffffffff81af4816: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81adfc20)
Location: net/ipv4/igmp.c:1427
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81adfc20-ffffffff81adfe4f: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1427
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81b9f1a0-ffffffff81b9f447: ____ip_mc_inc_group (STB_LOCAL)
ffffffff81d3c54b-ffffffff81d3c560: ____ip_mc_inc_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1434
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81d315a0-ffffffff81d3186a: ____ip_mc_inc_group (STB_LOCAL)
ffffffff81f08d7d-ffffffff81f08d92: ____ip_mc_inc_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1434
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81ef9d80-ffffffff81efa04d: ____ip_mc_inc_group (STB_LOCAL)
ffffffff820b06ce-ffffffff820b06e3: ____ip_mc_inc_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1435
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81f59820-ffffffff81f59aed: ____ip_mc_inc_group (STB_LOCAL)
ffffffff8213194f-ffffffff82131964: ____ip_mc_inc_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/igmp.c (0)
Location: net/ipv4/igmp.c:1437
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff8201fcf0-ffffffff82020010: ____ip_mc_inc_group (STB_LOCAL)
ffffffff8221330d-ffffffff82213322: ____ip_mc_inc_group.cold (STB_LOCAL)
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
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cb0cf0)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffff800010cb0cf0-ffff800010cb0f0c: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbad0c)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
c0dbad0c-c0dbaf34: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc71b0)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
c000000000dc71b0-c000000000dc7480: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe00080835e)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffe00080835e-ffffffe000808546: ____ip_mc_inc_group (STB_LOCAL)
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
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81999730)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81999730-ffffffff8199991f: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819531f0)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff819531f0-ffffffff819533df: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a03fd0)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81a03fd0-ffffffff81a041bf: ____ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ____ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0e540)
Location: net/ipv4/igmp.c:1422
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81a0e540-ffffffff81a0e72f: ____ip_mc_inc_group (STB_LOCAL)
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
