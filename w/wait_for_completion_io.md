# Function: <code>wait_for_completion_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81821850)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - block/blk-lib.c:blkdev_issue_discard
  - block/blk-lib.c:blkdev_issue_write_same
  - block/blk-lib.c:blkdev_issue_zeroout
  - drivers/lightnvm/core.c:nvm_submit_ppa
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff81821850-ffffffff81821982: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff8189bcb0)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:__nvm_submit_ppa
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
ffffffff8189bcb0-ffffffff8189bde2: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff818d02c0)
Location: kernel/sched/completion.c:153
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:__nvm_submit_ppa
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff818d02c0-ffffffff818d03f3: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff819077b0)
Location: kernel/sched/completion.c:156
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_erase_sync
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff819077b0-ffffffff819078e3: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff819918a0)
Location: kernel/sched/completion.c:170
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff819918a0-ffffffff819919d8: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff819edef0)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff819edef0-ffffffff819ee02a: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a29120)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81a29120-ffffffff81a2925a: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a997e0)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81a997e0-ffffffff81a998f3: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81ad1130)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_io_wait
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81ad1130-ffffffff81ad1243: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81bc93c0)
Location: kernel/sched/completion.c:169
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81bc93c0-ffffffff81bc93e6: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81c421e0)
Location: kernel/sched/completion.c:169
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81c421e0-ffffffff81c42206: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81c34150)
Location: kernel/sched/completion.c:169
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_bb_chunk_sense
  - drivers/lightnvm/core.c:nvm_submit_io_sync
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81c34150-ffffffff81c34176: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81d52af0)
Location: kernel/sched/completion.c:169
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81d52af0-ffffffff81d52b16: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f231a0)
Location: kernel/sched/completion.c:169
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-mq.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81f231a0-ffffffff81f231d4: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cdf70)
Location: kernel/sched/completion.c:169
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-mq.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff820cdf70-ffffffff820ce0b3: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82151f90)
Location: kernel/sched/completion.c:169
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-mq.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff82151f90-ffffffff821520d3: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82234ae0)
Location: kernel/sched/completion.c:179
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-mq.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff82234ae0-ffffffff82234c23: wait_for_completion_io (STB_GLOBAL)
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
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffff800010da2bc0)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_io_wait
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffff800010da2bc0-ffff800010da2bfc: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c0e9a89c)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_io_wait
  - drivers/md/dm-io.c:dm_io
```
**Symbols:**

```
c0e9a89c-c0e9a9ec: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c000000000ee3de0)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_io_wait
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
c000000000ee3de0-c000000000ee400c: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffe0008c5cc4)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_io_wait
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffe0008c5cc4-ffffffe0008c5e44: wait_for_completion_io (STB_GLOBAL)
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
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a6ffa0)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_io_wait
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81a6ffa0-ffffffff81a700b3: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a2c3a0)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81a2c3a0-ffffffff81a2c4a7: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81adc3b0)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_io_wait
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81adc3b0-ffffffff81adc4c3: wait_for_completion_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wait_for_completion_io(struct completion *x);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81ae80b0)
Location: kernel/sched/completion.c:167
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_io_wait
  - drivers/md/dm-io.c:sync_io
```
**Symbols:**

```
ffffffff81ae80b0-ffffffff81ae81ac: wait_for_completion_io (STB_GLOBAL)
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
