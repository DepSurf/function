# Function: <code>blk_mq_debugfs_unregister_sched</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8145a443)
Location: block/blk-mq-debugfs.c:948
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_sched
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff8145a470-ffffffff8145a497: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814861c3)
Location: block/blk-mq-debugfs.c:949
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff814861f0-ffffffff81486217: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814bb0f3)
Location: block/blk-mq-debugfs.c:975
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff814bb120-ffffffff814bb147: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cf2c2)
Location: block/blk-mq-debugfs.c:1014
Inline: True
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff814cf2f0-ffffffff814cf317: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fdad0)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff814fdad0-ffffffff814fdaf7: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151ba20)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff8151ba20-ffffffff8151ba47: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157c1b0)
Location: block/blk-mq-debugfs.c:940
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff8157c1b0-ffffffff8157c1da: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81599250)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff81599250-ffffffff8159927a: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815a0050)
Location: block/blk-mq-debugfs.c:934
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff815a0050-ffffffff815a007a: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81608870)
Location: block/blk-mq-debugfs.c:935
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff81608870-ffffffff8160889a: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bc470)
Location: block/blk-mq-debugfs.c:793
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff816bc470-ffffffff816bc4a0: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177ce50)
Location: block/blk-mq-debugfs.c:793
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff8177ce50-ffffffff8177ce80: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bc7f0)
Location: block/blk-mq-debugfs.c:767
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff817bc7f0-ffffffff817bc820: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81800eb0)
Location: block/blk-mq-debugfs.c:748
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff81800eb0-ffffffff81800ee0: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
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
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010624070)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffff800010624070-ffff8000106240a0: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb6b0)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
c07cb6b0-c07cb6dc: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c4b60)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
c0000000007c4b60-c0000000007c4bac: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000455c4e)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffe000455c4e-ffffffe000455c7e: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
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
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81514000)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff81514000-ffffffff81514027: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81504310)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff81504310-ffffffff81504337: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81510090)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff81510090-ffffffff815100b7: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_sched(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81529850)
Location: block/blk-mq-debugfs.c:936
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_exit_sched
```
**Symbols:**

```
ffffffff81529850-ffffffff81529877: blk_mq_debugfs_unregister_sched (STB_GLOBAL)
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
