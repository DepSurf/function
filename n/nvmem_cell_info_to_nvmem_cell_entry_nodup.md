# Function: <code>nvmem_cell_info_to_nvmem_cell_entry_nodup</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell_entry_nodup(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell_entry *cell);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be181a)
Location: drivers/nvmem/core.c:459
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
ffffffff81bdf4f0-ffffffff81bdf55f: nvmem_cell_info_to_nvmem_cell_entry_nodup (STB_LOCAL)
ffffffff81f0076f-ffffffff81f007af: nvmem_cell_info_to_nvmem_cell_entry_nodup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell_entry_nodup(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell_entry *cell);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8d18a)
Location: drivers/nvmem/core.c:459
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
ffffffff81d8ab40-ffffffff81d8abeb: nvmem_cell_info_to_nvmem_cell_entry_nodup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell_entry_nodup(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell_entry *cell);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfb78e)
Location: drivers/nvmem/core.c:467
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_one_cell
```
**Symbols:**

```
ffffffff81df9100-ffffffff81df91ce: nvmem_cell_info_to_nvmem_cell_entry_nodup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int nvmem_cell_info_to_nvmem_cell_entry_nodup(struct nvmem_device *nvmem, const struct nvmem_cell_info *info, struct nvmem_cell_entry *cell);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb254e)
Location: drivers/nvmem/core.c:551
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_device_cell_write
  - drivers/nvmem/core.c:nvmem_device_cell_read
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_one_cell
```
**Symbols:**

```
ffffffff81eaf780-ffffffff81eaf84e: nvmem_cell_info_to_nvmem_cell_entry_nodup (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
