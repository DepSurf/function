# Function: <code>device_is_dependent</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c62b0)
Location: drivers/base/core.c:105
Inline: False
Direct callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_is_dependent
```
**Symbols:**

```
ffffffff815c62b0-ffffffff815c6369: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815db470)
Location: drivers/base/core.c:106
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff815db470-ffffffff815db51e: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642490)
Location: drivers/base/core.c:106
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff81642490-ffffffff8164253e: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d7b0)
Location: drivers/base/core.c:103
Inline: True
```
**Symbols:**

```
ffffffff8167d7b0-ffffffff8167d85f: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d1d0)
Location: drivers/base/core.c:104
Inline: True
```
**Symbols:**

```
ffffffff8169d1d0-ffffffff8169d262: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d6470)
Location: drivers/base/core.c:104
Inline: True
```
**Symbols:**

```
ffffffff816d6470-ffffffff816d6505: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816fa4d0)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff816fa4d0-ffffffff816fa565: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b4630)
Location: drivers/base/core.c:125
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff817b4630-ffffffff817b471e: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c8e90)
Location: drivers/base/core.c:229
Inline: True
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff817c8e90-ffffffff817c8f8f: device_is_dependent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ac4a0)
Location: drivers/base/core.c:268
Inline: True
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff817ac4a0-ffffffff817ac5a4: device_is_dependent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81835700)
Location: drivers/base/core.c:280
Inline: True
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff81835700-ffffffff81835804: device_is_dependent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81977630)
Location: drivers/base/core.c:281
Inline: False
Direct callers:
  - drivers/base/core.c:fw_devlink_create_devlink
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_is_dependent
  - drivers/base/core.c:device_is_dependent
```
**Symbols:**

```
ffffffff81977630-ffffffff8197774e: device_is_dependent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae3fb0)
Location: drivers/base/core.c:355
Inline: False
Direct callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_is_dependent
  - drivers/base/core.c:device_is_dependent
```
**Symbols:**

```
ffffffff81ae3fb0-ffffffff81ae40ce: device_is_dependent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b322a0)
Location: drivers/base/core.c:300
Inline: False
Direct callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_is_dependent
  - drivers/base/core.c:device_is_dependent
```
**Symbols:**

```
ffffffff81b322a0-ffffffff81b323be: device_is_dependent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b899c0)
Location: drivers/base/core.c:303
Inline: False
Direct callers:
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:device_is_dependent
  - drivers/base/core.c:device_is_dependent
```
**Symbols:**

```
ffffffff81b899c0-ffffffff81b89ae1: device_is_dependent (STB_LOCAL)
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
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4d00)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffff8000108e4d00-ffff8000108e4dc0: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d3734)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
c09d3734-c09d37c8: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c00000000097a290)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
c00000000097a290-c00000000097a3bc: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579aec)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffe000579aec-ffffffe000579b70: device_is_dependent (STB_LOCAL)
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
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bfcc0)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff816bfcc0-ffffffff816bfd55: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169af70)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff8169af70-ffffffff8169b005: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816ee190)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff816ee190-ffffffff816ee225: device_is_dependent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int device_is_dependent(struct device *dev, void *target);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817089d0)
Location: drivers/base/core.c:117
Inline: True
Direct callers:
  - drivers/base/core.c:device_link_add
```
**Symbols:**

```
ffffffff817089d0-ffffffff81708a65: device_is_dependent (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
