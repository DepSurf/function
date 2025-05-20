# Function: <code>nvmem_cell_read_variable_le_u32</code>

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
int nvmem_cell_read_variable_le_u32(struct device *dev, const char *cell_id, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0b60)
Location: drivers/nvmem/core.c:1654
Inline: False
```
**Symbols:**

```
ffffffff819c0b60-ffffffff819c0bee: nvmem_cell_read_variable_le_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u32(struct device *dev, const char *cell_id, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1666
Inline: False
```
**Symbols:**

```
ffffffff81d3475d-ffffffff81d3477e: nvmem_cell_read_variable_le_u32.cold (STB_LOCAL)
ffffffff81a70340-ffffffff81a703ef: nvmem_cell_read_variable_le_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u32(struct device *dev, const char *cell_id, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1696
Inline: False
```
**Symbols:**

```
ffffffff81f00bce-ffffffff81f00bf3: nvmem_cell_read_variable_le_u32.cold (STB_LOCAL)
ffffffff81be19b0-ffffffff81be1a6b: nvmem_cell_read_variable_le_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u32(struct device *dev, const char *cell_id, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1699
Inline: False
```
**Symbols:**

```
ffffffff820aa9db-ffffffff820aaa00: nvmem_cell_read_variable_le_u32.cold (STB_LOCAL)
ffffffff81d8d350-ffffffff81d8d40b: nvmem_cell_read_variable_le_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u32(struct device *dev, const char *cell_id, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1881
Inline: False
```
**Symbols:**

```
ffffffff8212bf17-ffffffff8212bf3c: nvmem_cell_read_variable_le_u32.cold (STB_LOCAL)
ffffffff81dfb980-ffffffff81dfba3b: nvmem_cell_read_variable_le_u32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_read_variable_le_u32(struct device *dev, const char *cell_id, u32 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:1924
Inline: False
```
**Symbols:**

```
ffffffff8220dacf-ffffffff8220daf4: nvmem_cell_read_variable_le_u32.cold (STB_LOCAL)
ffffffff81eb1580-ffffffff81eb163b: nvmem_cell_read_variable_le_u32 (STB_GLOBAL)
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
