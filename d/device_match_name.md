# Function: <code>device_match_name</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9d60)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
ffffffff816f9d60-ffffffff816f9d82: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2d40)
Location: drivers/base/core.c:4050
Inline: False
```
**Symbols:**

```
ffffffff817b2d40-ffffffff817b2d62: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7520)
Location: drivers/base/core.c:4506
Inline: False
```
**Symbols:**

```
ffffffff817c7520-ffffffff817c7542: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aa990)
Location: drivers/base/core.c:4733
Inline: False
```
**Symbols:**

```
ffffffff817aa990-ffffffff817aa9b2: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833b50)
Location: drivers/base/core.c:4805
Inline: False
```
**Symbols:**

```
ffffffff81833b50-ffffffff81833b72: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81975330)
Location: drivers/base/core.c:4844
Inline: False
Direct callers:
  - drivers/base/component.c:component_compare_dev_name
```
**Symbols:**

```
ffffffff81975330-ffffffff8197535a: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae0b30)
Location: drivers/base/core.c:5063
Inline: False
Direct callers:
  - drivers/base/component.c:component_compare_dev_name
```
**Symbols:**

```
ffffffff81ae0b30-ffffffff81ae0b5a: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2ed50)
Location: drivers/base/core.c:5072
Inline: False
Direct callers:
  - drivers/base/component.c:component_compare_dev_name
```
**Symbols:**

```
ffffffff81b2ed50-ffffffff81b2ed7a: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b86550)
Location: drivers/base/core.c:5086
Inline: False
Direct callers:
  - drivers/base/component.c:component_compare_dev_name
```
**Symbols:**

```
ffffffff81b86550-ffffffff81b8657a: device_match_name (STB_GLOBAL)
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
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4258)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
ffff8000108e4258-ffff8000108e4298: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d2d70)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
c09d2d70-c09d2d9c: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000979720)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
c000000000979720-c00000000097976c: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe000579250)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
ffffffe000579250-ffffffe000579288: device_match_name (STB_GLOBAL)
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
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf550)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
ffffffff816bf550-ffffffff816bf572: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a800)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
ffffffff8169a800-ffffffff8169a822: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816eda20)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
ffffffff816eda20-ffffffff816eda42: device_match_name (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_match_name(struct device *dev, const void *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81708260)
Location: drivers/base/core.c:3577
Inline: False
```
**Symbols:**

```
ffffffff81708260-ffffffff81708282: device_match_name (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
