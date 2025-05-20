# Function: <code>of_icc_get_from_provider</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (0)
Location: drivers/interconnect/core.c:349
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct icc_node_data *of_icc_get_from_provider(struct of_phandle_args *spec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819dc940)
Location: drivers/interconnect/core.c:356
Inline: True
```
**Symbols:**

```
ffffffff819dc940-ffffffff819dca6a: of_icc_get_from_provider.part.0 (STB_LOCAL)
ffffffff819dca70-ffffffff819dca8d: of_icc_get_from_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct icc_node_data *of_icc_get_from_provider(struct of_phandle_args *spec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff819c2bc0)
Location: drivers/interconnect/core.c:356
Inline: True
```
**Symbols:**

```
ffffffff819c2bc0-ffffffff819c2ce0: of_icc_get_from_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct icc_node_data *of_icc_get_from_provider(struct of_phandle_args *spec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81a72470)
Location: drivers/interconnect/core.c:356
Inline: True
```
**Symbols:**

```
ffffffff81a72470-ffffffff81a72590: of_icc_get_from_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct icc_node_data *of_icc_get_from_provider(struct of_phandle_args *spec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81be3fc0)
Location: drivers/interconnect/core.c:356
Inline: True
```
**Symbols:**

```
ffffffff81be3fc0-ffffffff81be410b: of_icc_get_from_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct icc_node_data *of_icc_get_from_provider(struct of_phandle_args *spec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81d8fd70)
Location: drivers/interconnect/core.c:356
Inline: True
```
**Symbols:**

```
ffffffff81d8fd70-ffffffff81d8febb: of_icc_get_from_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct icc_node_data *of_icc_get_from_provider(struct of_phandle_args *spec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81dfda60)
Location: drivers/interconnect/core.c:355
Inline: True
```
**Symbols:**

```
ffffffff81dfda60-ffffffff81dfdbab: of_icc_get_from_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct icc_node_data *of_icc_get_from_provider(struct of_phandle_args *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/interconnect/core.c (ffffffff81eb4de0)
Location: drivers/interconnect/core.c:371
Inline: False
```
**Symbols:**

```
ffffffff81eb4de0-ffffffff81eb4f6f: of_icc_get_from_provider (STB_GLOBAL)
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
