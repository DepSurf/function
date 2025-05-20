# Function: <code>rq_completed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md, int rw, bool run_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1220)
Location: drivers/md/dm.c:1098
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_requeue_original_request
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:dm_softirq_done
  - drivers/md/dm.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff816a1220-ffffffff816a129a: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md, int rw, bool run_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170ee60)
Location: drivers/md/dm-rq.c:210
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8170ee60-ffffffff8170eec8: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md, int rw, bool run_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81740e90)
Location: drivers/md/dm-rq.c:207
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_softirq_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81740e90-ffffffff81740f20: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md, int rw, bool run_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175aa40)
Location: drivers/md/dm-rq.c:185
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8175aa40-ffffffff8175aadf: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md, int rw, bool run_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817ccc70)
Location: drivers/md/dm-rq.c:180
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff817ccc70-ffffffff817ccd0c: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md, int rw, bool run_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81815a30)
Location: drivers/md/dm-rq.c:180
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81815a30-ffffffff81815ac2: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818419d0)
Location: drivers/md/dm-rq.c:131
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff818419d0-ffffffff81841a1b: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818847f0)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff818847f0-ffffffff81884847: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818b66e0)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff818b66e0-ffffffff818b6737: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198756b)
Location: drivers/md/dm-rq.c:144
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198b50b)
Location: drivers/md/dm-rq.c:144
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8196fbfb)
Location: drivers/md/dm-rq.c:144
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81a18538)
Location: drivers/md/dm-rq.c:144
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81b8125c)
Location: drivers/md/dm-rq.c:143
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1f58c)
Location: drivers/md/dm-rq.c:142
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d8876c)
Location: drivers/md/dm-rq.c:144
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e3fe7c)
Location: drivers/md/dm-rq.c:144
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
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
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffff800010b0e6f0)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffff800010b0e6f0-ffff800010b0e758: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c0becb08)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
c0becb08-c0becb58: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c000000000c016c0)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
c000000000c016c0-c000000000c01758: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffe0006fba04)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffe0006fba04-ffffffe0006fba62: rq_completed (STB_LOCAL)
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
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8185c560)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8185c560-ffffffff8185c5b7: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81823b30)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81823b30-ffffffff81823b87: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818abb90)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff818abb90-ffffffff818abbe7: rq_completed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rq_completed(struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818c7dd0)
Location: drivers/md/dm-rq.c:147
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff818c7dd0-ffffffff818c7e27: rq_completed (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param removed. </b>
<code>bool run_queue</code>
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
