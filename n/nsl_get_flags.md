# Function: <code>nsl_get_flags</code>

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
In drivers/nvdimm/namespace_devs.c (ffffffff81895178)
Location: drivers/nvdimm/nd.h:83
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffffffff81898697)
Location: drivers/nvdimm/nd.h:83
Inline: True
Inline callers:
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
In drivers/nvdimm/namespace_devs.c (ffffffff819e07f4)
Location: drivers/nvdimm/nd.h:100
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffffffff819e24c9)
Location: drivers/nvdimm/nd.h:100
Inline: True
Inline callers:
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
In drivers/nvdimm/namespace_devs.c (ffffffff81b5c234)
Location: drivers/nvdimm/nd.h:100
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffffffff81b5e11a)
Location: drivers/nvdimm/nd.h:100
Inline: True
Inline callers:
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
In drivers/nvdimm/namespace_devs.c (ffffffff81baf800)
Location: drivers/nvdimm/nd.h:100
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffffffff81bb16db)
Location: drivers/nvdimm/nd.h:100
Inline: True
Inline callers:
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
In drivers/nvdimm/namespace_devs.c (ffffffff81c03c30)
Location: drivers/nvdimm/nd.h:100
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
```
```
In drivers/nvdimm/label.c (ffffffff81c05bcb)
Location: drivers/nvdimm/nd.h:100
Inline: True
Inline callers:
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
