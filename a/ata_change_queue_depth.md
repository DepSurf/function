# Function: <code>ata_change_queue_depth</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ata_change_queue_depth(struct ata_port *ap, struct ata_device *dev, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81bbefc0)
Location: drivers/ata/libata-sata.c:1031
Inline: True
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81bbefc0-ffffffff81bbf0a7: ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c16050)
Location: drivers/ata/libata-sata.c:1042
Inline: False
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81c16050-ffffffff81c1616a: ata_change_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_change_queue_depth(struct ata_port *ap, struct scsi_device *sdev, int queue_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sata.c (ffffffff81c6b230)
Location: drivers/ata/libata-sata.c:1054
Inline: False
Direct callers:
  - drivers/ata/libata-sata.c:ata_scsi_change_queue_depth
```
**Symbols:**

```
ffffffff81c6b230-ffffffff81c6b34a: ata_change_queue_depth (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ata_device *dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>ap, dev, sdev, queue_depth</code> ➡️ <code>ap, sdev, queue_depth</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
