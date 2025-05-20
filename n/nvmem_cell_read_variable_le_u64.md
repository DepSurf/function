# Function: <code>nvmem_cell_read_variable_le_u64</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvmem_cell_read_variable_le_u64(struct device *dev, const char *cell_id, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0bf0)
Location: drivers/nvmem/core.c:1685
Inline: False
```
**Symbols:**

```
ffffffff819c0bf0-ffffffff819c0c80: nvmem_cell_read_variable_le_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u64(struct device *dev, const char *cell_id, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1697
Inline: False
```
**Symbols:**

```
ffffffff81d3477e-ffffffff81d3479f: nvmem_cell_read_variable_le_u64.cold (STB_LOCAL)
ffffffff81a703f0-ffffffff81a704a1: nvmem_cell_read_variable_le_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u64(struct device *dev, const char *cell_id, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1727
Inline: False
```
**Symbols:**

```
ffffffff81f00bf3-ffffffff81f00c18: nvmem_cell_read_variable_le_u64.cold (STB_LOCAL)
ffffffff81be1a70-ffffffff81be1b2c: nvmem_cell_read_variable_le_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u64(struct device *dev, const char *cell_id, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1730
Inline: False
```
**Symbols:**

```
ffffffff820aaa00-ffffffff820aaa25: nvmem_cell_read_variable_le_u64.cold (STB_LOCAL)
ffffffff81d8d420-ffffffff81d8d4dc: nvmem_cell_read_variable_le_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u64(struct device *dev, const char *cell_id, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1912
Inline: False
```
**Symbols:**

```
ffffffff8212bf3c-ffffffff8212bf61: nvmem_cell_read_variable_le_u64.cold (STB_LOCAL)
ffffffff81dfba50-ffffffff81dfbb0c: nvmem_cell_read_variable_le_u64 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u64(struct device *dev, const char *cell_id, u64 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1955
Inline: False
```
**Symbols:**

```
ffffffff8220daf4-ffffffff8220db19: nvmem_cell_read_variable_le_u64.cold (STB_LOCAL)
ffffffff81eb1650-ffffffff81eb170c: nvmem_cell_read_variable_le_u64 (STB_GLOBAL)
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
