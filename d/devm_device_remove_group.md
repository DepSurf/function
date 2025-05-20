# Function: <code>devm_device_remove_group</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642390)
Location: drivers/base/core.c:1106
Inline: True
```
**Symbols:**

```
ffffffff81642390-ffffffff816423b9: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d630)
Location: drivers/base/core.c:1148
Inline: True
```
**Symbols:**

```
ffffffff8167d630-ffffffff8167d659: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d020)
Location: drivers/base/core.c:1222
Inline: True
```
**Symbols:**

```
ffffffff8169d020-ffffffff8169d049: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff816d89b8)
Location: drivers/base/core.c:1367
Inline: True
```
**Symbols:**

```
ffffffff816d89b8-ffffffff816d89cb: devm_device_remove_group.cold (STB_LOCAL)
ffffffff816d5ee0-ffffffff816d5f09: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9f20)
Location: drivers/base/core.c:1404
Inline: True
```
**Symbols:**

```
ffffffff816f9f20-ffffffff816f9f49: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2e50)
Location: drivers/base/core.c:1882
Inline: True
```
**Symbols:**

```
ffffffff817b2e50-ffffffff817b2e79: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c78b0)
Location: drivers/base/core.c:2283
Inline: True
```
**Symbols:**

```
ffffffff817c78b0-ffffffff817c78d9: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aad20)
Location: drivers/base/core.c:2495
Inline: True
```
**Symbols:**

```
ffffffff817aad20-ffffffff817aad49: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81832ff0)
Location: drivers/base/core.c:2551
Inline: False
```
**Symbols:**

```
ffffffff81832ff0-ffffffff81833019: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81974910)
Location: drivers/base/core.c:2562
Inline: False
```
**Symbols:**

```
ffffffff81974910-ffffffff81974955: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e4668)
Location: drivers/base/core.c:1404
Inline: True
```
**Symbols:**

```
ffff8000108e4668-ffff8000108e46c0: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d30a8)
Location: drivers/base/core.c:1404
Inline: True
```
**Symbols:**

```
c09d30a8-c09d30f8: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000978270)
Location: drivers/base/core.c:1404
Inline: False
```
**Symbols:**

```
c000000000978270-c0000000009782c8: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe00057956e)
Location: drivers/base/core.c:1404
Inline: True
```
**Symbols:**

```
ffffffe00057956e-ffffffe0005795c0: devm_device_remove_group (STB_GLOBAL)
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
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf710)
Location: drivers/base/core.c:1404
Inline: True
```
**Symbols:**

```
ffffffff816bf710-ffffffff816bf739: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a9c0)
Location: drivers/base/core.c:1404
Inline: True
```
**Symbols:**

```
ffffffff8169a9c0-ffffffff8169a9e9: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816edbe0)
Location: drivers/base/core.c:1404
Inline: True
```
**Symbols:**

```
ffffffff816edbe0-ffffffff816edc09: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_group(struct device *dev, const struct attribute_group *grp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81708420)
Location: drivers/base/core.c:1404
Inline: True
```
**Symbols:**

```
ffffffff81708420-ffffffff81708449: devm_device_remove_group (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
