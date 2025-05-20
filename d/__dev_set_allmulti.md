# Function: <code>__dev_set_allmulti</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171dc40)
Location: net/core/dev.c:5778
Inline: False
Direct callers:
  - net/core/dev.c:dev_set_allmulti
  - net/core/dev.c:__dev_change_flags
```
**Symbols:**

```
ffffffff8171dc40-ffffffff8171dd3c: __dev_set_allmulti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81786510)
Location: net/core/dev.c:6229
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81786510-ffffffff8178660c: __dev_set_allmulti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b3ad0)
Location: net/core/dev.c:6373
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff817b3ad0-ffffffff817b3bcc: __dev_set_allmulti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d2460)
Location: net/core/dev.c:6538
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff817d2460-ffffffff817d255c: __dev_set_allmulti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184c700)
Location: net/core/dev.c:6695
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff8184c700-ffffffff8184c803: __dev_set_allmulti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6831
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81896970-ffffffff81896a73: __dev_set_allmulti (STB_LOCAL)
ffffffff81899235-ffffffff81899254: __dev_set_allmulti.cold.168 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7406
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff818b8be0-ffffffff818b8ce3: __dev_set_allmulti (STB_LOCAL)
ffffffff818bb6d7-ffffffff818bb6f6: __dev_set_allmulti.cold.175 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7416
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81904da0-ffffffff81904eac: __dev_set_allmulti (STB_LOCAL)
ffffffff819075f8-ffffffff81907619: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81937410-ffffffff8193751c: __dev_set_allmulti (STB_LOCAL)
ffffffff81939bdf-ffffffff81939c00: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8118
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81a0bf30-ffffffff81a0c054: __dev_set_allmulti (STB_LOCAL)
ffffffff81a0f17f-ffffffff81a0f1a0: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8363
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81a0d5f0-ffffffff81a0d71f: __dev_set_allmulti (STB_LOCAL)
ffffffff81c314ca-ffffffff81c314eb: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8622
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff819f4290-ffffffff819f43bf: __dev_set_allmulti (STB_LOCAL)
ffffffff81c237af-ffffffff81c237d0: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8612
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81aa5b90-ffffffff81aa5cd5: __dev_set_allmulti (STB_LOCAL)
ffffffff81d366ac-ffffffff81d366e8: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8378
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81c1d640-ffffffff81c1d778: __dev_set_allmulti (STB_LOCAL)
ffffffff81f02e80-ffffffff81f02eba: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8364
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81dce8f0-ffffffff81dcea4f: __dev_set_allmulti (STB_LOCAL)
ffffffff820ab768-ffffffff820ab783: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8368
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81e3f4f0-ffffffff81e3f679: __dev_set_allmulti (STB_LOCAL)
ffffffff8212cee4-ffffffff8212ceff: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8486
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81efde40-ffffffff81efdfc6: __dev_set_allmulti (STB_LOCAL)
ffffffff8220ec34-ffffffff8220ec4f: __dev_set_allmulti.cold (STB_LOCAL)
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
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd5e18)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffff800010bd5e18-ffff800010bd5f28: __dev_set_allmulti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf09b4)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
c0cf09b4-c0cf0ad4: __dev_set_allmulti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb55a0)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
c000000000cb55a0-c000000000cb5720: __dev_set_allmulti (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075f65c)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffe00075f65c-ffffffe00075f754: __dev_set_allmulti (STB_LOCAL)
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
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff818d73e0-ffffffff818d74ec: __dev_set_allmulti (STB_LOCAL)
ffffffff818d9baf-ffffffff818d9bd0: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81891220-ffffffff8189132c: __dev_set_allmulti (STB_LOCAL)
ffffffff818939ef-ffffffff81893a10: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81928410-ffffffff8192851c: __dev_set_allmulti (STB_LOCAL)
ffffffff8192abdf-ffffffff8192ac00: __dev_set_allmulti.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __dev_set_allmulti(struct net_device *dev, int inc, bool notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:7705
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_flags
  - net/core/dev.c:dev_set_allmulti
```
**Symbols:**

```
ffffffff81949ae0-ffffffff81949bec: __dev_set_allmulti (STB_LOCAL)
ffffffff8194c2af-ffffffff8194c2d0: __dev_set_allmulti.cold (STB_LOCAL)
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
