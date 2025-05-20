# Function: <code>blk_queue_flush_queueable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_queue_flush_queueable(struct request_queue *q, bool queueable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff813be260)
Location: block/blk-settings.c:843
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff813be260-ffffffff813be284: blk_queue_flush_queueable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_queue_flush_queueable(struct request_queue *q, bool queueable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814021c0)
Location: block/blk-settings.c:823
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814021c0-ffffffff8140220f: blk_queue_flush_queueable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_queue_flush_queueable(struct request_queue *q, bool queueable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8141c860)
Location: block/blk-settings.c:847
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8141c860-ffffffff8141c8af: blk_queue_flush_queueable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_queue_flush_queueable(struct request_queue *q, bool queueable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8142a7c0)
Location: block/blk-settings.c:859
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff8142a7c0-ffffffff8142a80f: blk_queue_flush_queueable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_queue_flush_queueable(struct request_queue *q, bool queueable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81455030)
Location: block/blk-settings.c:860
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81455030-ffffffff8145507f: blk_queue_flush_queueable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_queue_flush_queueable(struct request_queue *q, bool queueable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81488bb0)
Location: block/blk-settings.c:860
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff81488bb0-ffffffff81488bd4: blk_queue_flush_queueable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_queue_flush_queueable(struct request_queue *q, bool queueable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff814a2ad0)
Location: block/blk-settings.c:802
Inline: False
Direct callers:
  - drivers/ata/libata-scsi.c:ata_scsi_dev_config
```
**Symbols:**

```
ffffffff814a2ad0-ffffffff814a2af4: blk_queue_flush_queueable (STB_GLOBAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
