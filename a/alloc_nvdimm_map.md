# Function: <code>alloc_nvdimm_map</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff815ec026)
Location: drivers/nvdimm/core.c:85
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81618c16)
Location: drivers/nvdimm/core.c:85
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8162cd66)
Location: drivers/nvdimm/core.c:85
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816954f6)
Location: drivers/nvdimm/core.c:85
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d15bd)
Location: drivers/nvdimm/core.c:85
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816f2c4d)
Location: drivers/nvdimm/core.c:85
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8172c21c)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8175046c)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct nvdimm_map *alloc_nvdimm_map(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:77
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff8180ebe0-ffffffff8180ed62: alloc_nvdimm_map (STB_LOCAL)
ffffffff8180f10c-ffffffff8180f136: alloc_nvdimm_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct nvdimm_map *alloc_nvdimm_map(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:77
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff8181d750-ffffffff8181d8d2: alloc_nvdimm_map (STB_LOCAL)
ffffffff81c15a4e-ffffffff81c15a78: alloc_nvdimm_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct nvdimm_map *alloc_nvdimm_map(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:77
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff818009c0-ffffffff81800b42: alloc_nvdimm_map (STB_LOCAL)
ffffffff81c07787-ffffffff81c077b1: alloc_nvdimm_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct nvdimm_map *alloc_nvdimm_map(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:77
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff8188adc0-ffffffff8188af58: alloc_nvdimm_map (STB_LOCAL)
ffffffff81d0ad7c-ffffffff81d0adbb: alloc_nvdimm_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct nvdimm_map *alloc_nvdimm_map(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:78
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff819d4500-ffffffff819d46aa: alloc_nvdimm_map (STB_LOCAL)
ffffffff81ed320d-ffffffff81ed3250: alloc_nvdimm_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct nvdimm_map *alloc_nvdimm_map(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:78
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff81b4ed50-ffffffff81b4ef2b: alloc_nvdimm_map (STB_LOCAL)
ffffffff8209a5ef-ffffffff8209a604: alloc_nvdimm_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct nvdimm_map *alloc_nvdimm_map(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:78
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff81ba21a0-ffffffff81ba2379: alloc_nvdimm_map (STB_LOCAL)
ffffffff8211b6cf-ffffffff8211b6e4: alloc_nvdimm_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct nvdimm_map *alloc_nvdimm_map(struct device *dev, resource_size_t offset, size_t size, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/core.c (0)
Location: drivers/nvdimm/core.c:78
Inline: False
Direct callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
**Symbols:**

```
ffffffff81bf6330-ffffffff81bf6538: alloc_nvdimm_map (STB_LOCAL)
ffffffff821f9556-ffffffff821f956b: alloc_nvdimm_map.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffff80001094fea0)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (c0000000009fcb08)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffe0005c02b8)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81704b5c)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d85dc)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8174392c)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8175ed7c)
Location: drivers/nvdimm/core.c:77
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:devm_nvdimm_memremap
```
</details>
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
