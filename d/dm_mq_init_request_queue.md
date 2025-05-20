# Function: <code>dm_mq_init_request_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170fe50)
Location: drivers/md/dm-rq.c:916
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8170fe50-ffffffff8170ffd2: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81741e30)
Location: drivers/md/dm-rq.c:922
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81741e30-ffffffff81741fbd: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175b8f0)
Location: drivers/md/dm-rq.c:777
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8175b8f0-ffffffff8175ba82: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817cdb30)
Location: drivers/md/dm-rq.c:774
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff817cdb30-ffffffff817cdcb9: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:787
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81816ac1-ffffffff81816ad8: dm_mq_init_request_queue.cold.11 (STB_LOCAL)
ffffffff81816920-ffffffff81816a7d: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81842230)
Location: drivers/md/dm-rq.c:517
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81842230-ffffffff8184237d: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81885090)
Location: drivers/md/dm-rq.c:536
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81885090-ffffffff818851dd: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818b7010)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff818b7010-ffffffff818b7162: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff819879b0)
Location: drivers/md/dm-rq.c:530
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff819879b0-ffffffff81987b02: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198b940)
Location: drivers/md/dm-rq.c:531
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8198b940-ffffffff8198ba88: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81970030)
Location: drivers/md/dm-rq.c:531
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81970030-ffffffff81970183: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81a18940)
Location: drivers/md/dm-rq.c:539
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81a18940-ffffffff81a18a8a: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81b81730)
Location: drivers/md/dm-rq.c:532
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81b81730-ffffffff81b81886: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1fb20)
Location: drivers/md/dm-rq.c:533
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81d1fb20-ffffffff81d1fc76: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d88d10)
Location: drivers/md/dm-rq.c:536
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81d88d10-ffffffff81d88e65: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e40420)
Location: drivers/md/dm-rq.c:536
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81e40420-ffffffff81e405a2: dm_mq_init_request_queue (STB_GLOBAL)
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
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffff800010b0f088)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffff800010b0f088-ffff800010b0f1d8: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c0bed3e8)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
c0bed3e8-c0bed534: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c000000000c023f0)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
c000000000c023f0-c000000000c025dc: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffe0006fc21a)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffe0006fc21a-ffffffe0006fc358: dm_mq_init_request_queue (STB_GLOBAL)
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
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8185ce90)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff8185ce90-ffffffff8185cfe2: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81824460)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff81824460-ffffffff818245b2: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818ac4c0)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff818ac4c0-ffffffff818ac612: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_mq_init_request_queue(struct mapped_device *md, struct dm_table *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818c8710)
Location: drivers/md/dm-rq.c:537
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
```
**Symbols:**

```
ffffffff818c8710-ffffffff818c8862: dm_mq_init_request_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
