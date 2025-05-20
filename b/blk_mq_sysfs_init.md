# Function: <code>blk_mq_sysfs_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff813c8284)
Location: block/blk-mq-sysfs.c:411
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_register_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff8140c4ac)
Location: block/blk-mq-sysfs.c:420
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_register_disk
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814278a8)
Location: block/blk-mq-sysfs.c:479
Inline: True
Inline callers:
  - block/blk-mq-sysfs.c:blk_mq_register_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81434d30)
Location: block/blk-mq-sysfs.c:292
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81434d30-ffffffff81434daf: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81460940)
Location: block/blk-mq-sysfs.c:292
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81460940-ffffffff814609b6: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81494220)
Location: block/blk-mq-sysfs.c:285
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81494220-ffffffff81494296: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814ae360)
Location: block/blk-mq-sysfs.c:297
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814ae360-ffffffff814ae3e7: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814dc600)
Location: block/blk-mq-sysfs.c:302
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814dc600-ffffffff814dc67e: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814f5a70)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814f5a70-ffffffff814f5aee: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81556410)
Location: block/blk-mq-sysfs.c:299
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81556410-ffffffff8155648e: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff81572c60)
Location: block/blk-mq-sysfs.c:297
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81572c60-ffffffff81572cde: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff8157ac80)
Location: block/blk-mq-sysfs.c:297
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8157ac80-ffffffff8157acfe: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff815dff80)
Location: block/blk-mq-sysfs.c:242
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815dff80-ffffffff815e0019: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff8168e850)
Location: block/blk-mq-sysfs.c:240
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8168e850-ffffffff8168e8f0: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff8174d1b0)
Location: block/blk-mq-sysfs.c:230
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8174d1b0-ffffffff8174d259: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff817897d0)
Location: block/blk-mq-sysfs.c:204
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff817897d0-ffffffff81789879: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff817cbf70)
Location: block/blk-mq-sysfs.c:204
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff817cbf70-ffffffff817cc013: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffff8000105f5d38)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffff8000105f5d38-ffff8000105f5de8: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (c07a167c)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
c07a167c-c07a1708: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (c00000000078dc50)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
c00000000078dc50-c00000000078dd3c: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffe000433906)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffe000433906-ffffffe0004339b8: blk_mq_sysfs_init (STB_GLOBAL)
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
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814ee050)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814ee050-ffffffff814ee0ce: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814de5a0)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814de5a0-ffffffff814de61e: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff814ea0e0)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814ea0e0-ffffffff814ea15e: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_sysfs_init(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sysfs.c (ffffffff815030b0)
Location: block/blk-mq-sysfs.c:307
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815030b0-ffffffff8150312e: blk_mq_sysfs_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
