# Function: <code>kblockd_mod_delayed_work_on</code>

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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421960)
Location: block/blk-core.c:3196
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff81421960-ffffffff81421980: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144c4a0)
Location: block/blk-core.c:3420
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff8144c4a0-ffffffff8144c4c0: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8147f740)
Location: block/blk-core.c:3571
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff8147f740-ffffffff8147f760: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149d1c0)
Location: block/blk-core.c:1677
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff8149d1c0-ffffffff8149d1e0: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb360)
Location: block/blk-core.c:1628
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff814cb360-ffffffff814cb380: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4550)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff814e4550-ffffffff814e4570: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81542d90)
Location: block/blk-core.c:1760
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_add_to_requeue_list
```
**Symbols:**

```
ffffffff81542d90-ffffffff81542db0: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f6a0)
Location: block/blk-core.c:1654
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_add_to_requeue_list
```
**Symbols:**

```
ffffffff8155f6a0-ffffffff8155f6c0: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567e40)
Location: block/blk-core.c:1646
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_add_to_requeue_list
```
**Symbols:**

```
ffffffff81567e40-ffffffff81567e60: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc490)
Location: block/blk-core.c:1632
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_add_to_requeue_list
```
**Symbols:**

```
ffffffff815cc490-ffffffff815cc4b0: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81678250)
Location: block/blk-core.c:1097
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_add_to_requeue_list
```
**Symbols:**

```
ffffffff81678250-ffffffff8167827c: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81733920)
Location: block/blk-core.c:1035
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_add_to_requeue_list
```
**Symbols:**

```
ffffffff81733920-ffffffff8173394c: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176fd40)
Location: block/blk-core.c:1034
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_requeue_request
```
**Symbols:**

```
ffffffff8176fd40-ffffffff8176fd6c: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b1fb0)
Location: block/blk-core.c:1069
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_requeue_request
```
**Symbols:**

```
ffffffff817b1fb0-ffffffff817b1fdc: kblockd_mod_delayed_work_on (STB_GLOBAL)
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e0958)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffff8000105e0958-ffff8000105e09ac: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078ebe0)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
c078ebe0-c078ec10: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774e10)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
  - block/blk-mq.c:blk_mq_add_to_requeue_list
```
**Symbols:**

```
c000000000774e10-c000000000774e5c: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423c8a)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffe000423c8a-ffffffe000423cce: kblockd_mod_delayed_work_on (STB_GLOBAL)
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
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dcb30)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff814dcb30-ffffffff814dcb50: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd4e0)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff814cd4e0-ffffffff814cd500: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d8bc0)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff814d8bc0-ffffffff814d8be0: kblockd_mod_delayed_work_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kblockd_mod_delayed_work_on(int cpu, struct delayed_work *dwork, long unsigned int delay);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f17d0)
Location: block/blk-core.c:1669
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_delay_run_hw_queue
  - block/blk-mq.c:blk_mq_delay_kick_requeue_list
```
**Symbols:**

```
ffffffff814f17d0-ffffffff814f17f0: kblockd_mod_delayed_work_on (STB_GLOBAL)
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
