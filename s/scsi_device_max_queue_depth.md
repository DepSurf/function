# Function: <code>scsi_device_max_queue_depth</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_max_queue_depth(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818225f2)
Location: drivers/scsi/scsi.c:221
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81822cd0-ffffffff81822cee: scsi_device_max_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_max_queue_depth(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818acf32)
Location: drivers/scsi/scsi.c:214
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff818ad5f0-ffffffff818ad60e: scsi_device_max_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_max_queue_depth(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7cce)
Location: drivers/scsi/scsi.c:205
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff819f8300-ffffffff819f8326: scsi_device_max_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_max_queue_depth(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b755be)
Location: drivers/scsi/scsi.c:205
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff81b75ce0-ffffffff81b75d06: scsi_device_max_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_max_queue_depth(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc8eee)
Location: drivers/scsi/scsi.c:205
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff81bc9600-ffffffff81bc9626: scsi_device_max_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int scsi_device_max_queue_depth(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1ddde)
Location: drivers/scsi/scsi.c:205
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_track_queue_full
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
  - drivers/scsi/scsi_scan.c:scsi_realloc_sdev_budget_map
```
**Symbols:**

```
ffffffff81c1e1f0-ffffffff81c1e216: scsi_device_max_queue_depth (STB_GLOBAL)
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
