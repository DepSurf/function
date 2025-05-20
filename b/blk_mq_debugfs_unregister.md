# Function: <code>blk_mq_debugfs_unregister</code>

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
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8145a5d1)
Location: block/blk-mq-debugfs.c:839
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8145a130-ffffffff8145a162: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81486368)
Location: block/blk-mq-debugfs.c:840
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81485eb0-ffffffff81485ee2: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814bb298)
Location: block/blk-mq-debugfs.c:866
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814bade0-ffffffff814bae12: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cf5c3)
Location: block/blk-mq-debugfs.c:905
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814cefa0-ffffffff814cefd2: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fd830)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff814fd830-ffffffff814fd862: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151b780)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8151b780-ffffffff8151b7b2: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157bef0)
Location: block/blk-mq-debugfs.c:861
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8157bef0-ffffffff8157bf25: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81598fb0)
Location: block/blk-mq-debugfs.c:859
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff81598fb0-ffffffff81598fc6: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159fdb0)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff8159fdb0-ffffffff8159fdc6: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816085d0)
Location: block/blk-mq-debugfs.c:858
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_release_queue
```
**Symbols:**

```
ffffffff816085d0-ffffffff816085e6: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
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
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010623dc0)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffff800010623dc0-ffff800010623df4: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb430)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c07cb430-c07cb460: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c4770)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
c0000000007c4770-c0000000007c47c0: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe0004559f4)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffe0004559f4-ffffffe000455a28: blk_mq_debugfs_unregister (STB_GLOBAL)
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
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81513d60)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81513d60-ffffffff81513d92: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81504070)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81504070-ffffffff815040a2: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8150fdf0)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8150fdf0-ffffffff8150fe22: blk_mq_debugfs_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815295b0)
Location: block/blk-mq-debugfs.c:857
Inline: False
Direct callers:
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff815295b0-ffffffff815295e2: blk_mq_debugfs_unregister (STB_GLOBAL)
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
