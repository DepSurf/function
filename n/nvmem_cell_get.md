# Function: <code>nvmem_cell_get</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *cell_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5ab1)
Location: drivers/nvmem/core.c:857
Inline: True
Inline callers:
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff817a5b20-ffffffff817a5b6f: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *cell_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181d51c)
Location: drivers/nvmem/core.c:860
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff8181cca0-ffffffff8181ccef: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *cell_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81867776)
Location: drivers/nvmem/core.c:929
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_get
```
**Symbols:**

```
ffffffff81866bc0-ffffffff81866cd7: nvmem_cell_get.part.14 (STB_LOCAL)
ffffffff81866ce0-ffffffff81866d00: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81887826)
Location: drivers/nvmem/core.c:1066
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81886b70-ffffffff81886b8d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818d19a9)
Location: drivers/nvmem/core.c:816
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818d1140-ffffffff818d115d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81903da9)
Location: drivers/nvmem/core.c:813
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81903540-ffffffff8190355d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819db69b)
Location: drivers/nvmem/core.c:1073
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819da8e0-ffffffff819da8fd: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819dac5b)
Location: drivers/nvmem/core.c:1251
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819d9770-ffffffff819d978d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0ab5)
Location: drivers/nvmem/core.c:1254
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff819bfa10-ffffffff819bfa2d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a70295)
Location: drivers/nvmem/core.c:1265
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81a6f060-ffffffff81a6f07d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be18c5)
Location: drivers/nvmem/core.c:1278
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81be02f0-ffffffff81be031d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8d255)
Location: drivers/nvmem/core.c:1281
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81d8bb20-ffffffff81d8bb4d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfb885)
Location: drivers/nvmem/core.c:1454
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81dfa190-ffffffff81dfa1bd: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb14a5)
Location: drivers/nvmem/core.c:1496
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_variable_common
  - drivers/nvmem/core.c:nvmem_cell_read_common
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81eb1310-ffffffff81eb133d: nvmem_cell_get (STB_GLOBAL)
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
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9f568)
Location: drivers/nvmem/core.c:813
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffff800010b9f568-ffff800010b9f6f0: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c8125c)
Location: drivers/nvmem/core.c:813
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
c0c8125c-c0c813d0: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c72a20)
Location: drivers/nvmem/core.c:813
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
c000000000c72a20-c000000000c73078: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe0007377d0)
Location: drivers/nvmem/core.c:813
Inline: True
Direct callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffe0007377d0-ffffffe000737920: nvmem_cell_get (STB_GLOBAL)
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
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818a31d9)
Location: drivers/nvmem/core.c:813
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818a2970-ffffffff818a298d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8185e949)
Location: drivers/nvmem/core.c:813
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff8185e0e0-ffffffff8185e0fd: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818f47c9)
Location: drivers/nvmem/core.c:813
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff818f3f60-ffffffff818f3f7d: nvmem_cell_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct nvmem_cell *nvmem_cell_get(struct device *dev, const char *id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81915869)
Location: drivers/nvmem/core.c:813
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_cell_read_u32
  - drivers/nvmem/core.c:nvmem_cell_read_u16
  - drivers/nvmem/core.c:devm_nvmem_cell_get
Direct callers:
  - net/ethernet/eth.c:nvmem_get_mac_address
```
**Symbols:**

```
ffffffff81915000-ffffffff8191501d: nvmem_cell_get (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *id</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *cell_id</code>
</li>
</ul>
</details>
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
