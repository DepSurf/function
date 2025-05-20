# Function: <code>nvmem_cell_read_u8</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int nvmem_cell_read_u8(struct device *dev, const char *cell_id, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819dad90)
Location: drivers/nvmem/core.c:1558
Inline: False
```
**Symbols:**

```
ffffffff819dad90-ffffffff819dada5: nvmem_cell_read_u8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int nvmem_cell_read_u8(struct device *dev, const char *cell_id, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0a30)
Location: drivers/nvmem/core.c:1561
Inline: False
```
**Symbols:**

```
ffffffff819c0a30-ffffffff819c0a45: nvmem_cell_read_u8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int nvmem_cell_read_u8(struct device *dev, const char *cell_id, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a70210)
Location: drivers/nvmem/core.c:1573
Inline: False
```
**Symbols:**

```
ffffffff81a70210-ffffffff81a70225: nvmem_cell_read_u8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int nvmem_cell_read_u8(struct device *dev, const char *cell_id, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be1d80)
Location: drivers/nvmem/core.c:1603
Inline: False
```
**Symbols:**

```
ffffffff81be1d80-ffffffff81be1da1: nvmem_cell_read_u8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int nvmem_cell_read_u8(struct device *dev, const char *cell_id, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8d760)
Location: drivers/nvmem/core.c:1606
Inline: False
```
**Symbols:**

```
ffffffff81d8d760-ffffffff81d8d781: nvmem_cell_read_u8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int nvmem_cell_read_u8(struct device *dev, const char *cell_id, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfbef0)
Location: drivers/nvmem/core.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81dfbef0-ffffffff81dfbf11: nvmem_cell_read_u8 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int nvmem_cell_read_u8(struct device *dev, const char *cell_id, u8 *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb18b0)
Location: drivers/nvmem/core.c:1831
Inline: False
```
**Symbols:**

```
ffffffff81eb18b0-ffffffff81eb18d1: nvmem_cell_read_u8 (STB_GLOBAL)
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
