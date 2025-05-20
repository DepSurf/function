# Function: <code>nvmem_cell_info_to_nvmem_cell_nodup</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell_nodup(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819da51b)
Location: drivers/nvmem/core.c:448
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
ffffffff819d8fa0-ffffffff819d8ff0: nvmem_cell_info_to_nvmem_cell_nodup (STB_LOCAL)
ffffffff81c30108-ffffffff81c30137: nvmem_cell_info_to_nvmem_cell_nodup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell_nodup(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819c0ff2)
Location: drivers/nvmem/core.c:448
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff819bf0f0-ffffffff819bf143: nvmem_cell_info_to_nvmem_cell_nodup (STB_LOCAL)
ffffffff81c223d6-ffffffff81c22405: nvmem_cell_info_to_nvmem_cell_nodup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell_nodup(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell *cell);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a70832)
Location: drivers/nvmem/core.c:454
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_cells
```
**Symbols:**

```
ffffffff81a6e5c0-ffffffff81a6e613: nvmem_cell_info_to_nvmem_cell_nodup (STB_LOCAL)
ffffffff81d34380-ffffffff81d343af: nvmem_cell_info_to_nvmem_cell_nodup.cold (STB_LOCAL)
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
</ul>
