# Function: <code>devm_device_remove_groups</code>

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
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816423c0)
Location: drivers/base/core.c:1159
Inline: True
```
**Symbols:**

```
ffffffff816423c0-ffffffff816423e9: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167d660)
Location: drivers/base/core.c:1201
Inline: True
```
**Symbols:**

```
ffffffff8167d660-ffffffff8167d689: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169d050)
Location: drivers/base/core.c:1275
Inline: True
```
**Symbols:**

```
ffffffff8169d050-ffffffff8169d079: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff816d89cb)
Location: drivers/base/core.c:1420
Inline: True
```
**Symbols:**

```
ffffffff816d89cb-ffffffff816d89de: devm_device_remove_groups.cold (STB_LOCAL)
ffffffff816d5f10-ffffffff816d5f39: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f9f50)
Location: drivers/base/core.c:1457
Inline: True
```
**Symbols:**

```
ffffffff816f9f50-ffffffff816f9f79: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2e80)
Location: drivers/base/core.c:1935
Inline: True
```
**Symbols:**

```
ffffffff817b2e80-ffffffff817b2ea9: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c78e0)
Location: drivers/base/core.c:2336
Inline: True
```
**Symbols:**

```
ffffffff817c78e0-ffffffff817c7909: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aad50)
Location: drivers/base/core.c:2548
Inline: True
```
**Symbols:**

```
ffffffff817aad50-ffffffff817aad79: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833020)
Location: drivers/base/core.c:2604
Inline: False
```
**Symbols:**

```
ffffffff81833020-ffffffff81833049: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81974960)
Location: drivers/base/core.c:2615
Inline: False
```
**Symbols:**

```
ffffffff81974960-ffffffff819749a5: devm_device_remove_groups (STB_GLOBAL)
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
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e46c0)
Location: drivers/base/core.c:1457
Inline: True
```
**Symbols:**

```
ffff8000108e46c0-ffff8000108e4718: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d30f8)
Location: drivers/base/core.c:1457
Inline: True
```
**Symbols:**

```
c09d30f8-c09d3148: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c0000000009782d0)
Location: drivers/base/core.c:1457
Inline: False
```
**Symbols:**

```
c0000000009782d0-c000000000978328: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005795c0)
Location: drivers/base/core.c:1457
Inline: True
```
**Symbols:**

```
ffffffe0005795c0-ffffffe000579612: devm_device_remove_groups (STB_GLOBAL)
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
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816bf740)
Location: drivers/base/core.c:1457
Inline: True
```
**Symbols:**

```
ffffffff816bf740-ffffffff816bf769: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169a9f0)
Location: drivers/base/core.c:1457
Inline: True
```
**Symbols:**

```
ffffffff8169a9f0-ffffffff8169aa19: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816edc10)
Location: drivers/base/core.c:1457
Inline: True
```
**Symbols:**

```
ffffffff816edc10-ffffffff816edc39: devm_device_remove_groups (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_device_remove_groups(struct device *dev, const struct attribute_group **groups);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81708450)
Location: drivers/base/core.c:1457
Inline: True
```
**Symbols:**

```
ffffffff81708450-ffffffff81708479: devm_device_remove_groups (STB_GLOBAL)
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
