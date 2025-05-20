# Function: <code>nvmem_cell_read_common</code>

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
int nvmem_cell_read_common(struct device *dev, const char *cell_id, void *val, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819db670)
Location: drivers/nvmem/core.c:1343
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u64
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
```
**Symbols:**

```
ffffffff819db670-ffffffff819db7ca: nvmem_cell_read_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvmem_cell_read_common(struct device *dev, const char *cell_id, void *val, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819dac30)
Location: drivers/nvmem/core.c:1521
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u64
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u8
```
**Symbols:**

```
ffffffff819dac30-ffffffff819dad8a: nvmem_cell_read_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvmem_cell_read_common(struct device *dev, const char *cell_id, void *val, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c08d0)
Location: drivers/nvmem/core.c:1524
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u64
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u8
```
**Symbols:**

```
ffffffff819c08d0-ffffffff819c0a2a: nvmem_cell_read_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nvmem_cell_read_common(struct device *dev, const char *cell_id, void *val, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a700b0)
Location: drivers/nvmem/core.c:1536
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u64
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u8
```
**Symbols:**

```
ffffffff81a700b0-ffffffff81a7020a: nvmem_cell_read_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nvmem_cell_read_common(struct device *dev, const char *cell_id, void *val, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be1bb0)
Location: drivers/nvmem/core.c:1566
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u64
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u8
```
**Symbols:**

```
ffffffff81be1bb0-ffffffff81be1d73: nvmem_cell_read_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvmem_cell_read_common(struct device *dev, const char *cell_id, void *val, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8d580)
Location: drivers/nvmem/core.c:1569
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u64
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u8
```
**Symbols:**

```
ffffffff81d8d580-ffffffff81d8d743: nvmem_cell_read_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvmem_cell_read_common(struct device *dev, const char *cell_id, void *val, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfbd10)
Location: drivers/nvmem/core.c:1751
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u64
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u8
```
**Symbols:**

```
ffffffff81dfbd10-ffffffff81dfbed3: nvmem_cell_read_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvmem_cell_read_common(struct device *dev, const char *cell_id, void *val, size_t count);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb1720)
Location: drivers/nvmem/core.c:1794
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u64
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u8
```
**Symbols:**

```
ffffffff81eb1720-ffffffff81eb1896: nvmem_cell_read_common (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
