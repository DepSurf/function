# Function: <code>generic_start_io_acct</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void generic_start_io_acct(int rw, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b05b0)
Location: block/bio.c:1675
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff813b05b0-ffffffff813b06ad: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void generic_start_io_acct(int rw, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4120)
Location: block/bio.c:1674
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff813f4120-ffffffff813f421e: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void generic_start_io_acct(int rw, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140db10)
Location: block/bio.c:1729
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff8140db10-ffffffff8140dc0e: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void generic_start_io_acct(int rw, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b770)
Location: block/bio.c:1735
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff8141b770-ffffffff8141b86e: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int rw, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814463a0)
Location: block/bio.c:1699
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff814463a0-ffffffff8144647a: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int rw, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81479340)
Location: block/bio.c:1756
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffff81479340-ffffffff8147941a: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81499bb0)
Location: block/bio.c:1680
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffff81499bb0-ffffffff81499cce: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c7c40)
Location: block/bio.c:1729
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffff814c7c40-ffffffff814c7d65: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e0d40)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffff814e0d40-ffffffff814e0e65: generic_start_io_acct (STB_GLOBAL)
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
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dd910)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffff8000105dd910-ffff8000105dda78: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078accc)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
c078accc-c078adf8: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076f1c0)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
c00000000076f1c0-c00000000076f368: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00042092e)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffe00042092e-ffffffe000420a2e: generic_start_io_acct (STB_GLOBAL)
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
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d9320)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffff814d9320-ffffffff814d9445: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c9cd0)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/nvdimm/pmem.c:pmem_make_request
  - drivers/nvdimm/btt.c:btt_make_request
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffff814c9cd0-ffffffff814c9df5: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d53b0)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffff814d53b0-ffffffff814d54d5: generic_start_io_acct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void generic_start_io_acct(struct request_queue *q, int op, long unsigned int sectors, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814edf60)
Location: block/bio.c:1771
Inline: False
Direct callers:
  - drivers/md/dm.c:alloc_io
```
**Symbols:**

```
ffffffff814edf60-ffffffff814ee0b4: generic_start_io_acct (STB_GLOBAL)
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
<code>rw, sectors, part</code> ➡️ <code>q, rw, sectors, part</code>
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
<code>int op</code>
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
