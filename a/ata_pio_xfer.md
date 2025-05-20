# Function: <code>ata_pio_xfer</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd *qc, struct page *page, unsigned int offset, size_t xfer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff8185b620)
Location: drivers/ata/libata-sff.c:640
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
```
**Symbols:**

```
ffffffff8185b620-ffffffff8185b6af: ata_pio_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd *qc, struct page *page, unsigned int offset, size_t xfer_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff818ea150)
Location: drivers/ata/libata-sff.c:640
Inline: False
Direct callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
```
**Symbols:**

```
ffffffff818ea150-ffffffff818ea1df: ata_pio_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd *qc, struct page *page, unsigned int offset, size_t xfer_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81a3b840)
Location: drivers/ata/libata-sff.c:634
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
```
**Symbols:**

```
ffffffff81a3b840-ffffffff81a3b92a: ata_pio_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd *qc, struct page *page, unsigned int offset, size_t xfer_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81bc0ec0)
Location: drivers/ata/libata-sff.c:578
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
```
**Symbols:**

```
ffffffff81bc0ec0-ffffffff81bc0faa: ata_pio_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd *qc, struct page *page, unsigned int offset, size_t xfer_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81c18a70)
Location: drivers/ata/libata-sff.c:578
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
```
**Symbols:**

```
ffffffff81c18a70-ffffffff81c18b56: ata_pio_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ata_pio_xfer(struct ata_queued_cmd *qc, struct page *page, unsigned int offset, size_t xfer_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-sff.c (ffffffff81c6d7c0)
Location: drivers/ata/libata-sff.c:578
Inline: True
Direct callers:
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
  - drivers/ata/libata-sff.c:ata_pio_sector
```
**Symbols:**

```
ffffffff81c6d7c0-ffffffff81c6d8a3: ata_pio_xfer (STB_LOCAL)
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
