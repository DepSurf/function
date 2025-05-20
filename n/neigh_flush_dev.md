# Function: <code>neigh_flush_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81727950)
Location: net/core/neighbour.c:195
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
  - net/core/neighbour.c:neigh_ifdown
```
**Symbols:**

```
ffffffff81727950-ffffffff81727a8a: neigh_flush_dev.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81791460)
Location: net/core/neighbour.c:195
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81791460-ffffffff8179159b: neigh_flush_dev.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff817bed30)
Location: net/core/neighbour.c:196
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff817bed30-ffffffff817bee6b: neigh_flush_dev.isra.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff817dcd30)
Location: net/core/neighbour.c:232
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff817dcd30-ffffffff817dce71: neigh_flush_dev.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff818585c0)
Location: net/core/neighbour.c:232
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff818585c0-ffffffff81858701: neigh_flush_dev.isra.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff818a3a30)
Location: net/core/neighbour.c:235
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff818a3a30-ffffffff818a3b7b: neigh_flush_dev.isra.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818c6dc0)
Location: net/core/neighbour.c:289
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff818c6dc0-ffffffff818c6f5d: neigh_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81912f10)
Location: net/core/neighbour.c:289
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81912f10-ffffffff819130c5: neigh_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81945570)
Location: net/core/neighbour.c:286
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81945570-ffffffff81945725: neigh_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81a15510)
Location: net/core/neighbour.c:286
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81a15510-ffffffff81a15700: neigh_flush_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff81a15800)
Location: net/core/neighbour.c:288
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81a15800-ffffffff81a159f0: neigh_flush_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffffffff819fc360)
Location: net/core/neighbour.c:292
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff819fc360-ffffffff819fc557: neigh_flush_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:292
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81aae3a0-ffffffff81aae577: neigh_flush_dev.isra.0 (STB_LOCAL)
ffffffff81d36c02-ffffffff81d36c20: neigh_flush_dev.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:335
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81c270c0-ffffffff81c2729e: neigh_flush_dev.isra.0 (STB_LOCAL)
ffffffff81f03503-ffffffff81f03521: neigh_flush_dev.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:372
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81dd9c00-ffffffff81dd9dde: neigh_flush_dev.isra.0 (STB_LOCAL)
ffffffff820abcd9-ffffffff820abcf7: neigh_flush_dev.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:372
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81e4a950-ffffffff81e4ab31: neigh_flush_dev.isra.0 (STB_LOCAL)
ffffffff8212d430-ffffffff8212d44e: neigh_flush_dev.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:380
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81f09670-ffffffff81f09851: neigh_flush_dev.isra.0 (STB_LOCAL)
ffffffff8220f17d-ffffffff8220f19b: neigh_flush_dev.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (ffff800010be4400)
Location: net/core/neighbour.c:286
Inline: True
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffff800010be4400-ffff800010be45c4: neigh_flush_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cff1a4)
Location: net/core/neighbour.c:286
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
c0cff1a4-c0cff34c: neigh_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc8460)
Location: net/core/neighbour.c:286
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
c000000000cc8460-c000000000cc86e8: neigh_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076b4d2)
Location: net/core/neighbour.c:286
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffe00076b4d2-ffffffe00076b64e: neigh_flush_dev (STB_LOCAL)
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
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff818e5540)
Location: net/core/neighbour.c:286
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff818e5540-ffffffff818e56f5: neigh_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff8189f380)
Location: net/core/neighbour.c:286
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff8189f380-ffffffff8189f535: neigh_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81936570)
Location: net/core/neighbour.c:286
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81936570-ffffffff81936725: neigh_flush_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void neigh_flush_dev(struct neigh_table *tbl, struct net_device *dev, bool skip_perm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81957d00)
Location: net/core/neighbour.c:286
Inline: False
Direct callers:
  - net/core/neighbour.c:__neigh_ifdown
  - net/core/neighbour.c:neigh_changeaddr
```
**Symbols:**

```
ffffffff81957d00-ffffffff81957ebc: neigh_flush_dev (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
