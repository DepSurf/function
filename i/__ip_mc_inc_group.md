# Function: <code>__ip_mc_inc_group</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8192e540)
Location: net/ipv4/igmp.c:1390
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff8192e540-ffffffff8192e72e: __ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, unsigned int mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8195da80)
Location: net/ipv4/igmp.c:1403
Inline: False
Direct callers:
  - net/ipv4/igmp.c:__ip_mc_join_group
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff8195da80-ffffffff8195dc55: __ip_mc_inc_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819c39cf)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff819c2fe0-ffffffff819c2ff4: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff819fa56f)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff819f9b80-ffffffff819f9b94: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae8e7f)
Location: net/ipv4/igmp.c:1468
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81ae7940-ffffffff81ae7954: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81af5d8f)
Location: net/ipv4/igmp.c:1468
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81af4820-ffffffff81af4834: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ae14df)
Location: net/ipv4/igmp.c:1475
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81adfe50-ffffffff81adfe64: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81ba0bbf)
Location: net/ipv4/igmp.c:1475
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81b9f450-ffffffff81b9f464: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81d330af)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81d31870-ffffffff81d31890: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81efb38f)
Location: net/ipv4/igmp.c:1482
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81efa060-ffffffff81efa080: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81f5ae1f)
Location: net/ipv4/igmp.c:1483
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81f59b00-ffffffff81f59b20: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8202135f)
Location: net/ipv4/igmp.c:1485
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff82020020-ffffffff82020040: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffff800010cb1c80)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffff800010cb0f10-ffff800010cb0f58: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c0dbd8ac)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
c0dbaf34-c0dbaf58: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (c000000000dc8c7c)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
c000000000dc7480-c000000000dc749c: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffe00080a632)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffe000808546-ffffffe000808582: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff8199a30f)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81999920-ffffffff81999934: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81953dcf)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff819533e0-ffffffff819533f4: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a04baf)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81a041c0-ffffffff81a041d4: __ip_mc_inc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __ip_mc_inc_group(struct in_device *in_dev, __be32 addr, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/igmp.c (ffffffff81a0f13f)
Location: net/ipv4/igmp.c:1470
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_up
```
**Symbols:**

```
ffffffff81a0e730-ffffffff81a0e744: __ip_mc_inc_group (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int mode</code>
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
