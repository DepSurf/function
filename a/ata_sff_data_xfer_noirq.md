# Function: <code>ata_sff_data_xfer_noirq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int ata_sff_data_xfer_noirq(struct ata_device *dev, unsigned char *buf, unsigned int buflen, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff815dc570)
Location: drivers/ata/libata-sff.c:675
Inline: False
```
**Symbols:**

```
ffffffff815dc570-ffffffff815dc5a1: ata_sff_data_xfer_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int ata_sff_data_xfer_noirq(struct ata_device *dev, unsigned char *buf, unsigned int buflen, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff816362f0)
Location: drivers/ata/libata-sff.c:675
Inline: False
```
**Symbols:**

```
ffffffff816362f0-ffffffff81636321: ata_sff_data_xfer_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int ata_sff_data_xfer_noirq(struct ata_device *dev, unsigned char *buf, unsigned int buflen, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81667390)
Location: drivers/ata/libata-sff.c:675
Inline: False
```
**Symbols:**

```
ffffffff81667390-ffffffff816673c1: ata_sff_data_xfer_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int ata_sff_data_xfer_noirq(struct ata_queued_cmd *qc, unsigned char *buf, unsigned int buflen, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8167baf0)
Location: drivers/ata/libata-sff.c:676
Inline: False
```
**Symbols:**

```
ffffffff8167baf0-ffffffff8167bb21: ata_sff_data_xfer_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int ata_sff_data_xfer_noirq(struct ata_queued_cmd *qc, unsigned char *buf, unsigned int buflen, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff816e5190)
Location: drivers/ata/libata-sff.c:676
Inline: False
```
**Symbols:**

```
ffffffff816e5190-ffffffff816e51c1: ata_sff_data_xfer_noirq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int ata_sff_data_xfer_noirq(struct ata_queued_cmd *qc, unsigned char *buf, unsigned int buflen, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81721a30)
Location: drivers/ata/libata-sff.c:676
Inline: False
```
**Symbols:**

```
ffffffff81721a30-ffffffff81721a61: ata_sff_data_xfer_noirq (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ata_queued_cmd *qc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ata_device *dev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
