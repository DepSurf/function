# Function: <code>__dev_set_promiscuity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171d780)
Location: net/core/dev.c:5705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
  - net/core/dev.c:__dev_change_flags
```
**Symbols:**

```
ffffffff8171d780-ffffffff8171d94c: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81786050)
Location: net/core/dev.c:6156
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81786050-ffffffff8178621c: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b3610)
Location: net/core/dev.c:6300
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff817b3610-ffffffff817b37dc: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d1f90)
Location: net/core/dev.c:6465
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff817d1f90-ffffffff817d2153: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184c220)
Location: net/core/dev.c:6622
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff8184c220-ffffffff8184c3e6: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6758
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81896560-ffffffff81896635: __dev_set_promiscuity (STB_LOCAL)
ffffffff81899125-ffffffff81899235: __dev_set_promiscuity.cold.167 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7333
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff818b87d0-ffffffff818b88a5: __dev_set_promiscuity (STB_LOCAL)
ffffffff818bb5c7-ffffffff818bb6d7: __dev_set_promiscuity.cold.174 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7343
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81904980-ffffffff81904a60: __dev_set_promiscuity (STB_LOCAL)
ffffffff819074e6-ffffffff819075f8: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81936ff0-ffffffff819370d0: __dev_set_promiscuity (STB_LOCAL)
ffffffff81939acd-ffffffff81939bdf: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8045
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81a0baf0-ffffffff81a0bbd0: __dev_set_promiscuity (STB_LOCAL)
ffffffff81a0f06d-ffffffff81a0f17f: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8290
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81a0d180-ffffffff81a0d260: __dev_set_promiscuity (STB_LOCAL)
ffffffff81c313b8-ffffffff81c314ca: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8549
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff819f3e20-ffffffff819f3f00: __dev_set_promiscuity (STB_LOCAL)
ffffffff81c2369d-ffffffff81c237af: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8539
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81aa56d0-ffffffff81aa57bf: __dev_set_promiscuity (STB_LOCAL)
ffffffff81d36525-ffffffff81d3664c: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8306
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81c1d130-ffffffff81c1d21d: __dev_set_promiscuity (STB_LOCAL)
ffffffff81f02cf9-ffffffff81f02e23: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8292
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81dce230-ffffffff81dce444: __dev_set_promiscuity (STB_LOCAL)
ffffffff820ab6f6-ffffffff820ab70b: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8297
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81e3ee30-ffffffff81e3f042: __dev_set_promiscuity (STB_LOCAL)
ffffffff8212ce72-ffffffff8212ce87: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8415
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81efd790-ffffffff81efd9a0: __dev_set_promiscuity (STB_LOCAL)
ffffffff8220ebc2-ffffffff8220ebd7: __dev_set_promiscuity.cold (STB_LOCAL)
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
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd5800)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffff800010bd5800-ffff800010bd59f4: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf0454)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
c0cf0454-c0cf0660: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb4dc0)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
c000000000cb4dc0-c000000000cb505c: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075f1a0)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffe00075f1a0-ffffffe00075f35a: __dev_set_promiscuity (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff818d6fc0-ffffffff818d70a0: __dev_set_promiscuity (STB_LOCAL)
ffffffff818d9a9d-ffffffff818d9baf: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81890e00-ffffffff81890ee0: __dev_set_promiscuity (STB_LOCAL)
ffffffff818938dd-ffffffff818939ef: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff81927ff0-ffffffff819280d0: __dev_set_promiscuity (STB_LOCAL)
ffffffff8192aacd-ffffffff8192abdf: __dev_set_promiscuity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __dev_set_promiscuity(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7632
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:__dev_set_rx_mode
  - net/core/dev.c:dev_set_promiscuity
```
**Symbols:**

```
ffffffff819496c0-ffffffff819497a0: __dev_set_promiscuity (STB_LOCAL)
ffffffff8194c19d-ffffffff8194c2af: __dev_set_promiscuity.cold (STB_LOCAL)
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
