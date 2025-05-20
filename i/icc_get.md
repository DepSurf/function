# Function: <code>icc_get</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct icc_path *icc_get(struct device *dev, const int src_id, const int dst_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:693
Inline: False
```
**Symbols:**

```
ffffffff819dd5e9-ffffffff819dd607: icc_get.cold (STB_LOCAL)
ffffffff819dc810-ffffffff819dc8d1: icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct icc_path *icc_get(struct device *dev, const int src_id, const int dst_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:724
Inline: False
```
**Symbols:**

```
ffffffff81c302a9-ffffffff81c302c7: icc_get.cold (STB_LOCAL)
ffffffff819dbe60-ffffffff819dbf21: icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct icc_path *icc_get(struct device *dev, const int src_id, const int dst_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:724
Inline: False
```
**Symbols:**

```
ffffffff81c22587-ffffffff81c225a5: icc_get.cold (STB_LOCAL)
ffffffff819c2100-ffffffff819c21c1: icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct icc_path *icc_get(struct device *dev, const int src_id, const int dst_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:724
Inline: False
```
**Symbols:**

```
ffffffff81d348b5-ffffffff81d348d3: icc_get.cold (STB_LOCAL)
ffffffff81a71980-ffffffff81a71a41: icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct icc_path *icc_get(struct device *dev, const int src_id, const int dst_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:724
Inline: False
```
**Symbols:**

```
ffffffff81f00cc2-ffffffff81f00ce0: icc_get.cold (STB_LOCAL)
ffffffff81be33f0-ffffffff81be34bd: icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct icc_path *icc_get(struct device *dev, const int src_id, const int dst_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8f060)
Location: drivers/interconnect/core.c:724
Inline: False
```
**Symbols:**

```
ffffffff81d8f060-ffffffff81d8f144: icc_get (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct icc_path *icc_get(struct device *dev, const char *src, const char *dst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb4f80)
Location: drivers/interconnect/core.c:596
Inline: False
```
**Symbols:**

```
ffffffff81eb4f80-ffffffff81eb5154: icc_get (STB_GLOBAL)
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
