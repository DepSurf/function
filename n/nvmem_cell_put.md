# Function: <code>nvmem_cell_put</code>

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
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5900)
Location: drivers/nvmem/core.c:939
Inline: False
Direct callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_release
```
**Symbols:**

```
ffffffff817a5900-ffffffff817a592c: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181ca70)
Location: drivers/nvmem/core.c:942
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_release
```
**Symbols:**

```
ffffffff8181ca70-ffffffff8181ca9c: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81866b70)
Location: drivers/nvmem/core.c:1015
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_release
```
**Symbols:**

```
ffffffff81866b70-ffffffff81866b9c: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886fe0)
Location: drivers/nvmem/core.c:1152
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81886fe0-ffffffff81887014: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d19f0)
Location: drivers/nvmem/core.c:902
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818d11f0-ffffffff818d1204: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903df0)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819035f0-ffffffff81903604: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819db739)
Location: drivers/nvmem/core.c:1159
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819da990-ffffffff819da9a4: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819dacf9)
Location: drivers/nvmem/core.c:1337
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819d9820-ffffffff819d9834: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0afa)
Location: drivers/nvmem/core.c:1340
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819bfac0-ffffffff819bfad4: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a702da)
Location: drivers/nvmem/core.c:1351
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81a6f110-ffffffff81a6f124: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be1918)
Location: drivers/nvmem/core.c:1364
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81bdffc0-ffffffff81be0001: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8d2a8)
Location: drivers/nvmem/core.c:1367
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81d8b7b0-ffffffff81d8b7f1: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfb8d8)
Location: drivers/nvmem/core.c:1540
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81df9d10-ffffffff81df9d51: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb1400)
Location: drivers/nvmem/core.c:1582
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_release
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81eb1400-ffffffff81eb1460: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010ba03f0)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffff800010b9f018-ffff800010b9f044: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c81d44)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
c0c80dec-c0c80e0c: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c73e80)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
c000000000c72460-c000000000c72478: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000738462)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffe00073730e-ffffffe000737338: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a3220)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818a2a20-ffffffff818a2a34: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185e990)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff8185e190-ffffffff8185e1a4: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f4810)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818f4010-ffffffff818f4024: nvmem_cell_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void nvmem_cell_put(struct nvmem_cell *cell);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819158b0)
Location: drivers/nvmem/core.c:899
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_release
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819150b0-ffffffff819150c4: nvmem_cell_put (STB_GLOBAL)
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
