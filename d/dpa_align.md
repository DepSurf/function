# Function: <code>dpa_align</code>

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
long unsigned int dpa_align(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818116e0)
Location: drivers/nvdimm/dimm_devs.c:566
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
**Symbols:**

```
ffffffff818116e0-ffffffff818117bc: dpa_align (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int dpa_align(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818205a0)
Location: drivers/nvdimm/dimm_devs.c:696
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
**Symbols:**

```
ffffffff818205a0-ffffffff8182067c: dpa_align (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int dpa_align(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81803880)
Location: drivers/nvdimm/dimm_devs.c:696
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
**Symbols:**

```
ffffffff81803880-ffffffff8180395c: dpa_align (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int dpa_align(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:714
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
  - drivers/nvdimm/dimm_devs.c:nd_blk_available_dpa
  - drivers/nvdimm/dimm_devs.c:alias_dpa_busy
```
**Symbols:**

```
ffffffff8188e480-ffffffff8188e57d: dpa_align (STB_LOCAL)
ffffffff81d0aeb2-ffffffff81d0aeda: dpa_align.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int dpa_align(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:695
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff819d7b30-ffffffff819d7c43: dpa_align (STB_LOCAL)
ffffffff81ed335a-ffffffff81ed338c: dpa_align.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long unsigned int dpa_align(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:705
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81b529b0-ffffffff81b52ac3: dpa_align (STB_LOCAL)
ffffffff8209a643-ffffffff8209a675: dpa_align.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long unsigned int dpa_align(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:705
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81ba5e70-ffffffff81ba5f80: dpa_align (STB_LOCAL)
ffffffff8211b723-ffffffff8211b74d: dpa_align.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long unsigned int dpa_align(struct nd_region *nd_region);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:707
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:nd_pmem_available_dpa
  - drivers/nvdimm/dimm_devs.c:nd_pmem_max_contiguous_dpa
```
**Symbols:**

```
ffffffff81bfa0f0-ffffffff81bfa200: dpa_align (STB_LOCAL)
ffffffff821f95aa-ffffffff821f95d4: dpa_align.cold (STB_LOCAL)
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
