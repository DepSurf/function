# Function: <code>get_device_parent</code>

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
In drivers/base/core.c (ffffffff815474b0)
Location: drivers/base/core.c:779
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff815474b0-ffffffff81547672: get_device_parent.isra.19 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81599220)
Location: drivers/base/core.c:779
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81599220-ffffffff815993e2: get_device_parent.isra.19 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff815c6a60)
Location: drivers/base/core.c:1348
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff815c6a60-ffffffff815c6c22: get_device_parent.isra.22 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff815db800)
Location: drivers/base/core.c:1346
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff815db800-ffffffff815db9ba: get_device_parent.isra.24 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81642830)
Location: drivers/base/core.c:1481
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81642830-ffffffff816429ea: get_device_parent.isra.26 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff8167e770)
Location: drivers/base/core.c:1523
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8167e770-ffffffff8167e934: get_device_parent.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff8169e210)
Location: drivers/base/core.c:1597
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8169e210-ffffffff8169e3d5: get_device_parent.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff816d67e0)
Location: drivers/base/core.c:1745
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816d67e0-ffffffff816d6981: get_device_parent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff816fa8e0)
Location: drivers/base/core.c:1782
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816fa8e0-ffffffff816faa81: get_device_parent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b3b10)
Location: drivers/base/core.c:2262
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817b3b10-ffffffff817b3cc2: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c85a0)
Location: drivers/base/core.c:2671
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817c85a0-ffffffff817c8752: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ac180)
Location: drivers/base/core.c:2889
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817ac180-ffffffff817ac332: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81835330)
Location: drivers/base/core.c:2957
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81835330-ffffffff818354e2: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81976a80)
Location: drivers/base/core.c:2975
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81976a80-ffffffff81976c66: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae3660)
Location: drivers/base/core.c:3173
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81ae3660-ffffffff81ae3846: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b31960)
Location: drivers/base/core.c:3179
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81b31960-ffffffff81b31b3a: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b89230)
Location: drivers/base/core.c:3192
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81b89230-ffffffff81b89439: get_device_parent (STB_LOCAL)
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
In drivers/base/core.c (ffff8000108e4ee0)
Location: drivers/base/core.c:1782
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffff8000108e4ee0-ffff8000108e50d4: get_device_parent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d2494)
Location: drivers/base/core.c:1782
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
c09d2494-c09d264c: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097a6c0)
Location: drivers/base/core.c:1782
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
c00000000097a6c0-c00000000097a93c: get_device_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct kobject *get_device_parent(struct device *dev, struct device *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579d22)
Location: drivers/base/core.c:1782
Inline: False
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffe000579d22-ffffffe000579ebe: get_device_parent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff816c00d0)
Location: drivers/base/core.c:1782
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816c00d0-ffffffff816c0271: get_device_parent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff8169b380)
Location: drivers/base/core.c:1782
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8169b380-ffffffff8169b521: get_device_parent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff816ee5a0)
Location: drivers/base/core.c:1782
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816ee5a0-ffffffff816ee741: get_device_parent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff81708ac0)
Location: drivers/base/core.c:1782
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81708ac0-ffffffff81708c6a: get_device_parent.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
