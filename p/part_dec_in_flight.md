# Function: <code>part_dec_in_flight</code>

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
In block/bio.c (ffffffff813b072c)
Location: include/linux/genhd.h:403
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff813ba63d)
Location: include/linux/genhd.h:403
Inline: True
```
```
In block/blk-merge.c (ffffffff813c1916)
Location: include/linux/genhd.h:403
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
```
In drivers/nvdimm/core.c (ffffffff81596b70)
Location: include/linux/genhd.h:403
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_iostat_end
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
In block/bio.c (ffffffff813f42a2)
Location: include/linux/genhd.h:387
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff813fe3b7)
Location: include/linux/genhd.h:387
Inline: True
```
```
In block/blk-merge.c (ffffffff8140585d)
Location: include/linux/genhd.h:387
Inline: True
```
```
In drivers/nvdimm/core.c (ffffffff815eba83)
Location: include/linux/genhd.h:387
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:nd_iostat_end
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
In block/bio.c (ffffffff8140dc92)
Location: include/linux/genhd.h:378
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff81417d4e)
Location: include/linux/genhd.h:378
Inline: True
```
```
In block/blk-merge.c (ffffffff8141fad6)
Location: include/linux/genhd.h:378
Inline: True
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
In block/bio.c (ffffffff8141b8f2)
Location: include/linux/genhd.h:372
Inline: True
Inline callers:
  - block/bio.c:generic_end_io_acct
```
```
In block/blk-core.c (ffffffff81425b44)
Location: include/linux/genhd.h:372
Inline: True
```
```
In block/blk-merge.c (ffffffff8142d96a)
Location: include/linux/genhd.h:372
Inline: True
Inline callers:
  - block/blk-merge.c:attempt_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81464240)
Location: block/genhd.c:58
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff81464240-ffffffff81464286: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81497b60)
Location: block/genhd.c:58
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
```
**Symbols:**

```
ffffffff81497b60-ffffffff81497ba5: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814b1aa0)
Location: block/genhd.c:58
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814b1aa0-ffffffff814b1b0f: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814dfec0)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814dfec0-ffffffff814dff30: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f92f0)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814f92f0-ffffffff814f9360: part_dec_in_flight (STB_GLOBAL)
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
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffff8000105fab60)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffff8000105fab60-ffff8000105fac44: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c07a5cf4)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
c07a5cf4-c07a5db0: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (c000000000793ae0)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
c000000000793ae0-c000000000793bd0: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffe000436e94)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffe000436e94-ffffffe000436f24: part_dec_in_flight (STB_GLOBAL)
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
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814f18d0)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814f18d0-ffffffff814f1940: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814e1e00)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814e1e00-ffffffff814e1e70: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff814ed960)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff814ed960-ffffffff814ed9d0: part_dec_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void part_dec_in_flight(struct request_queue *q, struct hd_struct *part, int rw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815069e0)
Location: block/genhd.c:59
Inline: False
Direct callers:
  - block/bio.c:generic_end_io_acct
  - block/blk-core.c:blk_account_io_done
```
**Symbols:**

```
ffffffff815069e0-ffffffff81506a50: part_dec_in_flight (STB_GLOBAL)
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
