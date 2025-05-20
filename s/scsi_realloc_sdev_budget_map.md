# Function: <code>scsi_realloc_sdev_budget_map</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_realloc_sdev_budget_map(struct scsi_device *sdev, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81a03cd0-ffffffff81a03e9d: scsi_realloc_sdev_budget_map (STB_LOCAL)
ffffffff81ed5605-ffffffff81ed561e: scsi_realloc_sdev_budget_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int scsi_realloc_sdev_budget_map(struct scsi_device *sdev, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81b828b0-ffffffff81b82a7d: scsi_realloc_sdev_budget_map (STB_LOCAL)
ffffffff8209bc09-ffffffff8209bc22: scsi_realloc_sdev_budget_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int scsi_realloc_sdev_budget_map(struct scsi_device *sdev, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81bd65b0-ffffffff81bd6776: scsi_realloc_sdev_budget_map (STB_LOCAL)
ffffffff8211caa0-ffffffff8211caba: scsi_realloc_sdev_budget_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int scsi_realloc_sdev_budget_map(struct scsi_device *sdev, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi_scan.c (0)
Location: drivers/scsi/scsi_scan.c:217
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_add_lun
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81c2b200-ffffffff81c2b3c6: scsi_realloc_sdev_budget_map (STB_LOCAL)
ffffffff821fa950-ffffffff821fa96a: scsi_realloc_sdev_budget_map.cold (STB_LOCAL)
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
