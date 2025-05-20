# Function: <code>nvmem_cell_read</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a62c0)
Location: drivers/nvmem/core.c:1007
Inline: False
```
**Symbols:**

```
ffffffff817a62c0-ffffffff817a635b: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181d470)
Location: drivers/nvmem/core.c:1009
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
```
**Symbols:**

```
ffffffff8181d470-ffffffff8181d50b: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818676c0)
Location: drivers/nvmem/core.c:1082
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
```
**Symbols:**

```
ffffffff818676c0-ffffffff8186774d: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81887770)
Location: drivers/nvmem/core.c:1218
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81887770-ffffffff818877fd: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d1820)
Location: drivers/nvmem/core.c:973
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818d1820-ffffffff818d18a3: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903c20)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81903c20-ffffffff81903ca3: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819db5e0)
Location: drivers/nvmem/core.c:1230
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819db5e0-ffffffff819db663: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819dab80)
Location: drivers/nvmem/core.c:1408
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819dab80-ffffffff819dac2c: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0820)
Location: drivers/nvmem/core.c:1411
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819c0820-ffffffff819c08cc: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a70000)
Location: drivers/nvmem/core.c:1423
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81a70000-ffffffff81a700ac: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be1360)
Location: drivers/nvmem/core.c:1447
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81be1360-ffffffff81be141a: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8c2e0)
Location: drivers/nvmem/core.c:1450
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81d8c2e0-ffffffff81d8c39a: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfa960)
Location: drivers/nvmem/core.c:1623
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81dfa960-ffffffff81dfaa2f: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb0e70)
Location: drivers/nvmem/core.c:1666
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_attr_read
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81eb0e70-ffffffff81eb0f3f: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010ba0210)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffff800010ba0210-ffff800010ba02a8: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c81ba0)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
c0c81ba0-c0c81c18: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c73bf0)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
c000000000c73bf0-c000000000c73ce4: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe0007382ba)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffe0007382ba-ffffffe00073832e: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a3050)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818a3050-ffffffff818a30d3: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185e7c0)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff8185e7c0-ffffffff8185e843: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f4640)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818f4640-ffffffff818f46c3: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *nvmem_cell_read(struct nvmem_cell *cell, size_t *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819156e0)
Location: drivers/nvmem/core.c:970
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819156e0-ffffffff81915763: nvmem_cell_read (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
