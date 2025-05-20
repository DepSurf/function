# Function: <code>path_find</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct icc_path *path_find(struct device *dev, struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dc4e0)
Location: drivers/interconnect/core.c:175
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_get
```
**Symbols:**

```
ffffffff819dc4e0-ffffffff819dc804: path_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct icc_path *path_find(struct device *dev, struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dbb40)
Location: drivers/interconnect/core.c:177
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_get
```
**Symbols:**

```
ffffffff819dbb40-ffffffff819dbe5b: path_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct icc_path *path_find(struct device *dev, struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c1df0)
Location: drivers/interconnect/core.c:177
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_get
```
**Symbols:**

```
ffffffff819c1df0-ffffffff819c20f9: path_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct icc_path *path_find(struct device *dev, struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81a71670)
Location: drivers/interconnect/core.c:177
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_get
```
**Symbols:**

```
ffffffff81a71670-ffffffff81a71979: path_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct icc_path *path_find(struct device *dev, struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be30c0)
Location: drivers/interconnect/core.c:177
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_get
```
**Symbols:**

```
ffffffff81be30c0-ffffffff81be33e1: path_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct icc_path *path_find(struct device *dev, struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8ed20)
Location: drivers/interconnect/core.c:177
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_get
```
**Symbols:**

```
ffffffff81d8ed20-ffffffff81d8f041: path_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:176
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct icc_path *path_find(struct device *dev, struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb3660)
Location: drivers/interconnect/core.c:192
Inline: False
Direct callers:
  - drivers/interconnect/core.c:icc_get
```
**Symbols:**

```
ffffffff81eb3660-ffffffff81eb3979: path_find (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
