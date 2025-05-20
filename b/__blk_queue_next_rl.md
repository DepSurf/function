# Function: <code>__blk_queue_next_rl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request_list *__blk_queue_next_rl(struct request_list *rl, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff813d90f0)
Location: block/blk-cgroup.c:405
Inline: False
Direct callers:
  - block/blk-core.c:__blk_drain_queue
  - block/blk-core.c:blk_update_nr_requests
```
**Symbols:**

```
ffffffff813d90f0-ffffffff813d914d: __blk_queue_next_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request_list *__blk_queue_next_rl(struct request_list *rl, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8141ee70)
Location: block/blk-cgroup.c:405
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff8141ee70-ffffffff8141eec3: __blk_queue_next_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request_list *__blk_queue_next_rl(struct request_list *rl, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8143a430)
Location: block/blk-cgroup.c:406
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff8143a430-ffffffff8143a483: __blk_queue_next_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request_list *__blk_queue_next_rl(struct request_list *rl, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81447cf0)
Location: block/blk-cgroup.c:407
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff81447cf0-ffffffff81447d4d: __blk_queue_next_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request_list *__blk_queue_next_rl(struct request_list *rl, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814748f0)
Location: block/blk-cgroup.c:407
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:blk_set_queue_dying
  - block/blk-core.c:__blk_drain_queue
```
**Symbols:**

```
ffffffff814748f0-ffffffff8147494d: __blk_queue_next_rl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request_list *__blk_queue_next_rl(struct request_list *rl, struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814a8e70)
Location: block/blk-cgroup.c:418
Inline: False
Direct callers:
  - block/blk-core.c:blk_update_nr_requests
  - block/blk-core.c:blk_set_queue_dying
```
**Symbols:**

```
ffffffff814a8e70-ffffffff814a8ecc: __blk_queue_next_rl (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
