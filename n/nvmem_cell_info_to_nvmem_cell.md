# Function: <code>nvmem_cell_info_to_nvmem_cell</code>

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
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff817a5360)
Location: drivers/nvmem/core.c:330
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff817a5360-ffffffff817a53cc: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff8181c4d0)
Location: drivers/nvmem/core.c:330
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff8181c4d0-ffffffff8181c53c: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff818665f0)
Location: drivers/nvmem/core.c:330
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff818665f0-ffffffff8186665b: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81886280)
Location: drivers/nvmem/core.c:350
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff81886280-ffffffff818862eb: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:138
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff818d07d0-ffffffff818d0826: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
ffffffff818d1d56-ffffffff818d1d73: nvmem_cell_info_to_nvmem_cell.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff81902c00-ffffffff81902c8c: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
ffffffff81904156-ffffffff81904174: nvmem_cell_info_to_nvmem_cell.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819daf23)
Location: drivers/nvmem/core.c:358
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_add_cells_from_table
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff819d9d10-ffffffff819d9d98: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
ffffffff819db825-ffffffff819db83f: nvmem_cell_info_to_nvmem_cell.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819d99ae)
Location: drivers/nvmem/core.c:474
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_add_cells_from_table
  - drivers/nvmem/core.c:nvmem_add_cells_from_table
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_add_cells
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0400)
Location: drivers/nvmem/core.c:474
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_add_cells
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6fb66)
Location: drivers/nvmem/core.c:480
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
  - drivers/nvmem/core.c:nvmem_add_cells
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffff800010b9e8c0)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffff800010b9e8c0-ffff800010b9e984: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c0c8071c)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
c0c8071c-c0c807d0: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (c000000000c718e0)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
c000000000c718e0-c000000000c719dc: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffe000736c10)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffe000736c10-ffffffe000736cb6: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff818a2030-ffffffff818a20bc: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
ffffffff818a3586-ffffffff818a35a4: nvmem_cell_info_to_nvmem_cell.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff8185d7a0-ffffffff8185d82c: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
ffffffff8185ecf6-ffffffff8185ed14: nvmem_cell_info_to_nvmem_cell.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff818f3620-ffffffff818f36ac: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
ffffffff818f4b76-ffffffff818f4b94: nvmem_cell_info_to_nvmem_cell.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (0)
Location: drivers/nvmem/core.c:133
Inline: False
Direct callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
```
**Symbols:**

```
ffffffff819146c0-ffffffff8191474c: nvmem_cell_info_to_nvmem_cell (STB_LOCAL)
ffffffff81915c16-ffffffff81915c34: nvmem_cell_info_to_nvmem_cell.cold (STB_LOCAL)
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
