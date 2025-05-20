# Function: <code>scsi_bsg_register_queue</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bsg_device *scsi_bsg_register_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_bsg.c (ffffffff818c0df0)
Location: drivers/scsi/scsi_bsg.c:102
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff818c0df0-ffffffff818c0e25: scsi_bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bsg_device *scsi_bsg_register_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_bsg.c (ffffffff81a0d4c0)
Location: drivers/scsi/scsi_bsg.c:99
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81a0d4c0-ffffffff81a0d501: scsi_bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bsg_device *scsi_bsg_register_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_bsg.c (ffffffff81b8d330)
Location: drivers/scsi/scsi_bsg.c:99
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81b8d330-ffffffff81b8d371: scsi_bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bsg_device *scsi_bsg_register_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_bsg.c (ffffffff81be1340)
Location: drivers/scsi/scsi_bsg.c:99
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81be1340-ffffffff81be1381: scsi_bsg_register_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bsg_device *scsi_bsg_register_queue(struct scsi_device *sdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_bsg.c (ffffffff81c36370)
Location: drivers/scsi/scsi_bsg.c:99
Inline: False
Direct callers:
  - drivers/scsi/scsi_sysfs.c:scsi_sysfs_add_sdev
```
**Symbols:**

```
ffffffff81c36370-ffffffff81c363b1: scsi_bsg_register_queue (STB_GLOBAL)
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
