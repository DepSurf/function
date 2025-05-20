# Function: <code>icc_link_destroy</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int icc_link_destroy(struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dbfe0)
Location: drivers/interconnect/core.c:885
Inline: True
```
**Symbols:**

```
ffffffff819dbfe0-ffffffff819dc068: icc_link_destroy.part.0 (STB_LOCAL)
ffffffff819dc070-ffffffff819dc0cd: icc_link_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int icc_link_destroy(struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819db640)
Location: drivers/interconnect/core.c:916
Inline: True
```
**Symbols:**

```
ffffffff819db640-ffffffff819db6c8: icc_link_destroy.part.0 (STB_LOCAL)
ffffffff819db6d0-ffffffff819db72d: icc_link_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int icc_link_destroy(struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c18f0)
Location: drivers/interconnect/core.c:916
Inline: True
```
**Symbols:**

```
ffffffff819c18f0-ffffffff819c19d3: icc_link_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int icc_link_destroy(struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81a71170)
Location: drivers/interconnect/core.c:916
Inline: True
```
**Symbols:**

```
ffffffff81a71170-ffffffff81a71253: icc_link_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int icc_link_destroy(struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be2810)
Location: drivers/interconnect/core.c:916
Inline: True
```
**Symbols:**

```
ffffffff81be2810-ffffffff81be2905: icc_link_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int icc_link_destroy(struct icc_node *src, struct icc_node *dst);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8e410)
Location: drivers/interconnect/core.c:916
Inline: True
```
**Symbols:**

```
ffffffff81d8e410-ffffffff81d8e507: icc_link_destroy (STB_GLOBAL)
```
</details>
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
