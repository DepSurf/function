# Function: <code>blk_mq_debugfs_register_sched</code>

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
int blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8145a3e0)
Location: block/blk-mq-debugfs.c:923
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8145a3e0-ffffffff8145a46f: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81486160)
Location: block/blk-mq-debugfs.c:924
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81486160-ffffffff814861ef: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814bb090)
Location: block/blk-mq-debugfs.c:950
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814bb090-ffffffff814bb11f: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cf250)
Location: block/blk-mq-debugfs.c:989
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814cf250-ffffffff814cf2ea: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fda60)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814fda60-ffffffff814fdac5: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151b9b0)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8151b9b0-ffffffff8151ba15: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157c150)
Location: block/blk-mq-debugfs.c:921
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8157c150-ffffffff8157c1a8: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815991f0)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815991f0-ffffffff81599248: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159fff0)
Location: block/blk-mq-debugfs.c:915
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8159fff0-ffffffff815a0048: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81608810)
Location: block/blk-mq-debugfs.c:916
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81608810-ffffffff81608868: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bc3b0)
Location: block/blk-mq-debugfs.c:772
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff816bc3b0-ffffffff816bc46b: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177cd80)
Location: block/blk-mq-debugfs.c:772
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8177cd80-ffffffff8177ce3b: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bc720)
Location: block/blk-mq-debugfs.c:746
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff817bc720-ffffffff817bc7db: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81800de0)
Location: block/blk-mq-debugfs.c:727
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81800de0-ffffffff81800e9b: blk_mq_debugfs_register_sched (STB_GLOBAL)
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
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010624008)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffff800010624008-ffff80001062406c: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb648)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c07cb648-c07cb6b0: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c4ab0)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c0000000007c4ab0-c0000000007c4b58: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000455bee)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffe000455bee-ffffffe000455c4e: blk_mq_debugfs_register_sched (STB_GLOBAL)
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
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81513f90)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81513f90-ffffffff81513ff5: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815042a0)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815042a0-ffffffff81504305: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81510020)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81510020-ffffffff81510085: blk_mq_debugfs_register_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_debugfs_register_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815297e0)
Location: block/blk-mq-debugfs.c:917
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815297e0-ffffffff81529845: blk_mq_debugfs_register_sched (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
