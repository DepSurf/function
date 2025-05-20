# Function: <code>nsl_get_rawsize</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff818957fc)
Location: drivers/nvdimm/nd.h:107
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff8189a139)
Location: drivers/nvdimm/nd.h:107
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
In drivers/nvdimm/namespace_devs.c (ffffffff819dfca0)
Location: drivers/nvdimm/nd.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff819e2acc)
Location: drivers/nvdimm/nd.h:134
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
In drivers/nvdimm/namespace_devs.c (ffffffff81b5b683)
Location: drivers/nvdimm/nd.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff81b5e6b0)
Location: drivers/nvdimm/nd.h:134
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
In drivers/nvdimm/namespace_devs.c (ffffffff81baec27)
Location: drivers/nvdimm/nd.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff81bb1c60)
Location: drivers/nvdimm/nd.h:134
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
In drivers/nvdimm/namespace_devs.c (ffffffff81c02ff6)
Location: drivers/nvdimm/nd.h:134
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:select_pmem_id
```
```
In drivers/nvdimm/label.c (ffffffff81c06150)
Location: drivers/nvdimm/nd.h:134
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
