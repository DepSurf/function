# Function: <code>dm_get_md_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a30c0)
Location: drivers/md/dm.c:542
Inline: False
```
**Symbols:**

```
ffffffff816a30c0-ffffffff816a30d2: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81703910)
Location: drivers/md/dm.c:396
Inline: False
```
**Symbols:**

```
ffffffff81703910-ffffffff81703922: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817349ec)
Location: drivers/md/dm.c:396
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff817357d0-ffffffff817357e2: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174ddac)
Location: drivers/md/dm.c:391
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff8174ebd0-ffffffff8174ebe2: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bfe3c)
Location: drivers/md/dm.c:398
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_destroy
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff817c0e20-ffffffff817c0e2f: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81809530)
Location: drivers/md/dm.c:444
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff81809530-ffffffff81809542: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81835660)
Location: drivers/md/dm.c:444
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff81835660-ffffffff81835672: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818784c0)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff818784c0-ffffffff818784d2: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818aa300)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff818aa300-ffffffff818aa312: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197a770)
Location: drivers/md/dm.c:430
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff8197a770-ffffffff8197a782: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b001c8)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffff800010b001c8-ffff800010b001f0: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdfc38)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
c0bdfc38-c0bdfc54: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bef5b0)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
c000000000bef5b0-c000000000bef5c0: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f0756)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffe0006f0756-ffffffe0006f0778: dm_get_md_queue (STB_GLOBAL)
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
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81850180)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff81850180-ffffffff81850192: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81817790)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff81817790-ffffffff818177a2: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189f7b0)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff8189f7b0-ffffffff8189f7c2: dm_get_md_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct request_queue *dm_get_md_queue(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bba10)
Location: drivers/md/dm.c:426
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_kick_requeue_list
```
**Symbols:**

```
ffffffff818bba10-ffffffff818bba22: dm_get_md_queue (STB_GLOBAL)
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
