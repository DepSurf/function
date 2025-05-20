# Function: <code>part_inc_in_flight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b066e)
Location: include/linux/genhd.h:396
Inline: True
Inline callers:
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff813ba9ed)
Location: include/linux/genhd.h:396
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In drivers/nvdimm/core.c (ffffffff81596a89)
Location: include/linux/genhd.h:396
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:__nd_iostat_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f41e6)
Location: include/linux/genhd.h:380
Inline: True
Inline callers:
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff813fe78f)
Location: include/linux/genhd.h:380
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
```
In drivers/nvdimm/core.c (ffffffff815eb998)
Location: include/linux/genhd.h:380
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:__nd_iostat_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140dbd6)
Location: include/linux/genhd.h:371
Inline: True
Inline callers:
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff81418180)
Location: include/linux/genhd.h:371
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b836)
Location: include/linux/genhd.h:365
Inline: True
Inline callers:
  - block/bio.c:generic_start_io_acct
```
```
In block/blk-core.c (ffffffff81426016)
Location: include/linux/genhd.h:365
Inline: True
Inline callers:
  - block/blk-core.c:blk_account_io_start
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814641f0)
Location: block/genhd.c:48
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff814641f0-ffffffff81464236: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81497b10)
Location: block/genhd.c:48
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff81497b10-ffffffff81497b55: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b1a30)
Location: block/genhd.c:48
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff814b1a30-ffffffff814b1a9f: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814dfe50)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff814dfe50-ffffffff814dfec0: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f9280)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff814f9280-ffffffff814f92f0: part_inc_in_flight (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105faa88)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffff8000105faa88-ffff8000105fab5c: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a5c38)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
c07a5c38-c07a5cf4: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c0000000007939f0)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
c0000000007939f0-c000000000793ae0: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000436e04)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffe000436e04-ffffffe000436e94: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f1860)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff814f1860-ffffffff814f18d0: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e1d90)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff814e1d90-ffffffff814e1e00: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ed8f0)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff814ed8f0-ffffffff814ed960: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void part_inc_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81506970)
Location: block/genhd.c:49
Inline: False
Direct callers:
  - block/bio.c:generic_start_io_acct
  - block/blk-core.c:blk_account_io_start
```
**Symbols:**

```
ffffffff81506970-ffffffff815069e0: part_inc_in_flight (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
