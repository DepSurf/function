# Function: <code>blk_queue_init_tags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_queue_init_tags(struct request_queue *q, int depth, struct blk_queue_tag *tags, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff813bc2c0)
Location: block/blk-tag.c:163
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff813bc2c0-ffffffff813bc34c: blk_queue_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_queue_init_tags(struct request_queue *q, int depth, struct blk_queue_tag *tags, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff814000c0)
Location: block/blk-tag.c:163
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff814000c0-ffffffff8140014c: blk_queue_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_queue_init_tags(struct request_queue *q, int depth, struct blk_queue_tag *tags, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81419960)
Location: block/blk-tag.c:163
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81419960-ffffffff814199ec: blk_queue_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_queue_init_tags(struct request_queue *q, int depth, struct blk_queue_tag *tags, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81427890)
Location: block/blk-tag.c:163
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81427890-ffffffff8142791e: blk_queue_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_queue_init_tags(struct request_queue *q, int depth, struct blk_queue_tag *tags, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81452890)
Location: block/blk-tag.c:164
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81452890-ffffffff8145291e: blk_queue_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_queue_init_tags(struct request_queue *q, int depth, struct blk_queue_tag *tags, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-tag.c (ffffffff81485c60)
Location: block/blk-tag.c:164
Inline: False
Direct callers:
  - drivers/scsi/scsi_scan.c:scsi_alloc_sdev
```
**Symbols:**

```
ffffffff81485c60-ffffffff81485cef: blk_queue_init_tags (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
