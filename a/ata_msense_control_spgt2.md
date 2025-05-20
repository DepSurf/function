# Function: <code>ata_msense_control_spgt2</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ata_msense_control_spgt2(struct ata_device *dev, u8 *buf, u8 spg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c04f80)
Location: drivers/ata/libata-scsi.c:2262
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_msense_control
  - drivers/ata/libata-scsi.c:ata_msense_control
  - drivers/ata/libata-scsi.c:ata_msense_control
```
**Symbols:**

```
ffffffff81c04f80-ffffffff81c05080: ata_msense_control_spgt2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ata_msense_control_spgt2(struct ata_device *dev, u8 *buf, u8 spg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-scsi.c (ffffffff81c59d80)
Location: drivers/ata/libata-scsi.c:2213
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_msense_control
  - drivers/ata/libata-scsi.c:ata_msense_control
  - drivers/ata/libata-scsi.c:ata_msense_control
```
**Symbols:**

```
ffffffff81c59d80-ffffffff81c59e80: ata_msense_control_spgt2 (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
