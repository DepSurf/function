# Function: <code>blk_mq_tag_update_sched_shared_tags</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_tag_update_sched_shared_tags(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168d9b0)
Location: block/blk-mq-tag.c:660
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8168d9b0-ffffffff8168d9e6: blk_mq_tag_update_sched_shared_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_tag_update_sched_shared_tags(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174c210)
Location: block/blk-mq-tag.c:653
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8174c210-ffffffff8174c246: blk_mq_tag_update_sched_shared_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_tag_update_sched_shared_tags(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81788930)
Location: block/blk-mq-tag.c:660
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81788930-ffffffff81788966: blk_mq_tag_update_sched_shared_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_tag_update_sched_shared_tags(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817cb030)
Location: block/blk-mq-tag.c:660
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff817cb030-ffffffff817cb066: blk_mq_tag_update_sched_shared_tags (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
