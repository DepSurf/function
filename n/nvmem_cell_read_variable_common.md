# Function: <code>nvmem_cell_read_variable_common</code>

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
void *nvmem_cell_read_variable_common(struct device *dev, const char *cell_id, size_t max_len, size_t *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0ab0)
Location: drivers/nvmem/core.c:1612
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32
```
**Symbols:**

```
ffffffff819c0ab0-ffffffff819c0b60: nvmem_cell_read_variable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const void *nvmem_cell_read_variable_common(struct device *dev, const char *cell_id, size_t max_len, size_t *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a70290)
Location: drivers/nvmem/core.c:1624
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32
```
**Symbols:**

```
ffffffff81a70290-ffffffff81a70340: nvmem_cell_read_variable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const void *nvmem_cell_read_variable_common(struct device *dev, const char *cell_id, size_t max_len, size_t *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be18c0)
Location: drivers/nvmem/core.c:1654
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32
```
**Symbols:**

```
ffffffff81be18c0-ffffffff81be19a1: nvmem_cell_read_variable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const void *nvmem_cell_read_variable_common(struct device *dev, const char *cell_id, size_t max_len, size_t *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8d250)
Location: drivers/nvmem/core.c:1657
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32
```
**Symbols:**

```
ffffffff81d8d250-ffffffff81d8d331: nvmem_cell_read_variable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const void *nvmem_cell_read_variable_common(struct device *dev, const char *cell_id, size_t max_len, size_t *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfb880)
Location: drivers/nvmem/core.c:1839
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32
```
**Symbols:**

```
ffffffff81dfb880-ffffffff81dfb961: nvmem_cell_read_variable_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const void *nvmem_cell_read_variable_common(struct device *dev, const char *cell_id, size_t max_len, size_t *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb14a0)
Location: drivers/nvmem/core.c:1882
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u64
  - drivers/nvmem/core.c:nvmem_cell_read_variable_le_u32
```
**Symbols:**

```
ffffffff81eb14a0-ffffffff81eb156e: nvmem_cell_read_variable_common (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>const void *</code>
</li>
</ul>
</details>
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
