# Function: <code>__blk_mq_debugfs_rq_show</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81459750)
Location: block/blk-mq-debugfs.c:306
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff81459750-ffffffff81459880: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814854c0)
Location: block/blk-mq-debugfs.c:303
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814854c0-ffffffff814855f3: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814ba590)
Location: block/blk-mq-debugfs.c:365
Inline: False
Direct callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814ba590-ffffffff814ba6c9: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814ce6f0)
Location: block/blk-mq-debugfs.c:356
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814ce6f0-ffffffff814ce826: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fcfb0)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff814fcfb0-ffffffff814fd101: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151af00)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff8151af00-ffffffff8151b051: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157ba90)
Location: block/blk-mq-debugfs.c:328
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff8157ba90-ffffffff8157bbe1: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81598b50)
Location: block/blk-mq-debugfs.c:330
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff81598b50-ffffffff81598ca1: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159f960)
Location: block/blk-mq-debugfs.c:328
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff8159f960-ffffffff8159faad: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81608110)
Location: block/blk-mq-debugfs.c:329
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff81608110-ffffffff8160827e: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bbb20)
Location: block/blk-mq-debugfs.c:306
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff816bbb20-ffffffff816bbca2: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177c410)
Location: block/blk-mq-debugfs.c:306
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff8177c410-ffffffff8177c592: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bbf10)
Location: block/blk-mq-debugfs.c:280
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff817bbf10-ffffffff817bc092: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff818005d0)
Location: block/blk-mq-debugfs.c:279
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write2_next_rq_show
  - block/mq-deadline.c:deadline_read2_next_rq_show
  - block/mq-deadline.c:deadline_write1_next_rq_show
  - block/mq-deadline.c:deadline_read1_next_rq_show
  - block/mq-deadline.c:deadline_write0_next_rq_show
  - block/mq-deadline.c:deadline_read0_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff818005d0-ffffffff81800752: __blk_mq_debugfs_rq_show (STB_GLOBAL)
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
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010623040)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffff800010623040-ffff8000106231a8: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07caad0)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
c07caad0-c07cac54: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c3290)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
c0000000007c3290-c0000000007c35a0: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000454e86)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffe000454e86-ffffffe000454ff4: __blk_mq_debugfs_rq_show (STB_GLOBAL)
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
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815134e0)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff815134e0-ffffffff81513631: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815037f0)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff815037f0-ffffffff81503941: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8150f570)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff8150f570-ffffffff8150f6c1: __blk_mq_debugfs_rq_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __blk_mq_debugfs_rq_show(struct seq_file *m, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81528d90)
Location: block/blk-mq-debugfs.c:324
Inline: False
Direct callers:
  - block/mq-deadline.c:deadline_write_next_rq_show
  - block/mq-deadline.c:deadline_read_next_rq_show
  - block/blk-mq-debugfs.c:hctx_show_busy_rq
  - block/blk-mq-debugfs.c:blk_mq_debugfs_rq_show
```
**Symbols:**

```
ffffffff81528d90-ffffffff81528ee1: __blk_mq_debugfs_rq_show (STB_GLOBAL)
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
