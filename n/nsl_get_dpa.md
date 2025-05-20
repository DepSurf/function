# Function: <code>nsl_get_dpa</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81896fb9)
Location: drivers/nvdimm/nd.h:95
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:create_namespace_blk
  - drivers/nvdimm/namespace_devs.c:add_namespace_resource
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff8189a134)
Location: drivers/nvdimm/nd.h:95
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff819e00a9)
Location: drivers/nvdimm/nd.h:117
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff819e2ad1)
Location: drivers/nvdimm/nd.h:117
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81b5bad4)
Location: drivers/nvdimm/nd.h:117
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff81b5e6b5)
Location: drivers/nvdimm/nd.h:117
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81baf072)
Location: drivers/nvdimm/nd.h:117
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff81bb1c65)
Location: drivers/nvdimm/nd.h:117
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/namespace_devs.c (ffffffff81c03442)
Location: drivers/nvdimm/nd.h:117
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff81c06155)
Location: drivers/nvdimm/nd.h:117
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_active_count
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
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
