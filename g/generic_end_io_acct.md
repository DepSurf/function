# Function: <code>generic_end_io_acct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void generic_end_io_acct(int rw, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b06b0)
Location: block/bio.c:1689
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff813b06b0-ffffffff813b0762: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void generic_end_io_acct(int rw, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4220)
Location: block/bio.c:1688
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff813f4220-ffffffff813f42cf: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void generic_end_io_acct(int rw, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140dc10)
Location: block/bio.c:1743
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff8140dc10-ffffffff8140dcbf: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void generic_end_io_acct(int rw, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b870)
Location: block/bio.c:1749
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff8141b870-ffffffff8141b91f: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int rw, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446480)
Location: block/bio.c:1713
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81446480-ffffffff81446518: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int rw, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479420)
Location: block/bio.c:1770
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81479420-ffffffff814794b8: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81499cd0)
Location: block/bio.c:1696
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff81499cd0-ffffffff81499e2c: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7d70)
Location: block/bio.c:1745
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff814c7d70-ffffffff814c7eca: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e0e70)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff814e0e70-ffffffff814e0fca: generic_end_io_acct (STB_GLOBAL)
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
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dda78)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffff8000105dda78-ffff8000105ddc04: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078adf8)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
c078adf8-c078af60: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076f370)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
c00000000076f370-c00000000076f548: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe000420a2e)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffe000420a2e-ffffffe000420b6e: generic_end_io_acct (STB_GLOBAL)
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
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d9450)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff814d9450-ffffffff814d95aa: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c9e00)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_make_request
  - drivers/nvdimm/btt.c:btt_make_request
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff814c9e00-ffffffff814c9f5a: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d54e0)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff814d54e0-ffffffff814d563a: generic_end_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void generic_end_io_acct(struct request_queue *q, int req_op, struct hd_struct *part, long unsigned int start_time);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ee0c0)
Location: block/bio.c:1787
Inline: False
Direct callers:
  - drivers/md/dm.c:dec_pending
```
**Symbols:**

```
ffffffff814ee0c0-ffffffff814ee24f: generic_end_io_acct (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>rw, part, start_time</code> ➡️ <code>q, rw, part, start_time</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int req_op</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
</ul>
</details>
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
