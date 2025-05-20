# Function: <code>wait_for_completion_io_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81820ee0)
Location: kernel/sched/completion.c:173
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:nvm_submit_ppa
```
**Symbols:**

```
ffffffff81820ee0-ffffffff8182101a: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff8189b330)
Location: kernel/sched/completion.c:173
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:__nvm_submit_ppa
```
**Symbols:**

```
ffffffff8189b330-ffffffff8189b46a: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff818cf950)
Location: kernel/sched/completion.c:173
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/lightnvm/core.c:__nvm_submit_ppa
```
**Symbols:**

```
ffffffff818cf950-ffffffff818cfa8b: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff819070c0)
Location: kernel/sched/completion.c:176
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff819070c0-ffffffff819071fb: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81991040)
Location: kernel/sched/completion.c:190
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81991040-ffffffff81991180: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff819ed930)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff819ed930-ffffffff819eda6e: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a28890)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81a28890-ffffffff81a289ce: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a99060)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81a99060-ffffffff81a9917f: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81ad09b0)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81ad09b0-ffffffff81ad0acf: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81bc93f0)
Location: kernel/sched/completion.c:189
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81bc93f0-ffffffff81bc940f: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81c42210)
Location: kernel/sched/completion.c:189
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81c42210-ffffffff81c4222f: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81c34180)
Location: kernel/sched/completion.c:189
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81c34180-ffffffff81c3419f: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81d52b20)
Location: kernel/sched/completion.c:189
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81d52b20-ffffffff81d52b3f: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f231e0)
Location: kernel/sched/completion.c:189
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-mq.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81f231e0-ffffffff81f2320b: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cd9c0)
Location: kernel/sched/completion.c:189
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-mq.c:blk_execute_rq
```
**Symbols:**

```
ffffffff820cd9c0-ffffffff820cdb0b: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff821520f0)
Location: kernel/sched/completion.c:189
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-mq.c:blk_execute_rq
```
**Symbols:**

```
ffffffff821520f0-ffffffff8215223b: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82234da0)
Location: kernel/sched/completion.c:199
Inline: False
Direct callers:
  - block/bio.c:submit_bio_wait
  - block/blk-mq.c:blk_execute_rq
```
**Symbols:**

```
ffffffff82234da0-ffffffff82234eeb: wait_for_completion_io_timeout (STB_GLOBAL)
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
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffff800010da2c00)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffff800010da2c00-ffff800010da2c40: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c0e9ab68)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
c0e9ab68-c0e9acc8: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (c000000000ee4260)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
c000000000ee4260-c000000000ee44a0: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffe0008c62d0)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffe0008c62d0-ffffffe0008c6440: wait_for_completion_io_timeout (STB_GLOBAL)
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
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a6f820)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
```
**Symbols:**

```
ffffffff81a6f820-ffffffff81a6f93f: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81a2bc40)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
  - drivers/nvme/host/pci.c:__nvme_disable_io_queues
```
**Symbols:**

```
ffffffff81a2bc40-ffffffff81a2bd53: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81adbc30)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81adbc30-ffffffff81adbd4f: wait_for_completion_io_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int wait_for_completion_io_timeout(struct completion *x, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/completion.c (ffffffff81ae82e0)
Location: kernel/sched/completion.c:187
Inline: False
Direct callers:
  - block/blk-exec.c:blk_execute_rq
```
**Symbols:**

```
ffffffff81ae82e0-ffffffff81ae83e4: wait_for_completion_io_timeout (STB_GLOBAL)
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
