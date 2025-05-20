# Function: <code>rtnl_xdp_prog_skb</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818c98b0)
Location: net/core/rtnetlink.c:1369
Inline: False
```
**Symbols:**

```
ffffffff818c98b0-ffffffff818c9913: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819168a0)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
ffffffff819168a0-ffffffff81916903: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81948ee0)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
ffffffff81948ee0-ffffffff81948f44: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18cf0)
Location: net/core/rtnetlink.c:1405
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81a18cf0-ffffffff81a18d5a: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81a18ee0)
Location: net/core/rtnetlink.c:1417
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81a18ee0-ffffffff81a18f4a: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff819ffc80)
Location: net/core/rtnetlink.c:1419
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff819ffc80-ffffffff819ffcea: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1408
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81ab2740-ffffffff81ab27b9: rtnl_xdp_prog_skb (STB_LOCAL)
ffffffff81d36d9a-ffffffff81d36daf: rtnl_xdp_prog_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1448
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81c2b8c0-ffffffff81c2b94d: rtnl_xdp_prog_skb (STB_LOCAL)
ffffffff81f036ae-ffffffff81f036c3: rtnl_xdp_prog_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1459
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81dde550-ffffffff81dde5dd: rtnl_xdp_prog_skb (STB_LOCAL)
ffffffff820abe43-ffffffff820abe58: rtnl_xdp_prog_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1470
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81e4f780-ffffffff81e4f80d: rtnl_xdp_prog_skb (STB_LOCAL)
ffffffff8212d5af-ffffffff8212d5c4: rtnl_xdp_prog_skb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/rtnetlink.c (0)
Location: net/core/rtnetlink.c:1477
Inline: False
Direct callers:
  - net/core/rtnetlink.c:rtnl_xdp_fill
```
**Symbols:**

```
ffffffff81f0e7c0-ffffffff81f0e84d: rtnl_xdp_prog_skb (STB_LOCAL)
ffffffff8220f2fc-ffffffff8220f311: rtnl_xdp_prog_skb.cold (STB_LOCAL)
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
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffff800010bea900)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
ffff800010bea900-ffff800010bea990: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c0d02ab4)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
c0d02ab4-c0d02b3c: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (c000000000ccda80)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
c000000000ccda80-c000000000ccdb50: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffe00076e430)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
ffffffe00076e430-ffffffe00076e4ac: rtnl_xdp_prog_skb (STB_LOCAL)
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
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818e8eb0)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
ffffffff818e8eb0-ffffffff818e8f14: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff818a2cf0)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
ffffffff818a2cf0-ffffffff818a2d54: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff81939ee0)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
ffffffff81939ee0-ffffffff81939f44: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 rtnl_xdp_prog_skb(struct net_device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/rtnetlink.c (ffffffff8195b710)
Location: net/core/rtnetlink.c:1367
Inline: False
```
**Symbols:**

```
ffffffff8195b710-ffffffff8195b774: rtnl_xdp_prog_skb (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
