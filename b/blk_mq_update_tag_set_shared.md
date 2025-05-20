# Function: <code>blk_mq_update_tag_set_shared</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_update_tag_set_shared(struct blk_mq_tag_set *set, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156ca10)
Location: block/blk-mq.c:2891
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8156ca10-ffffffff8156caaf: blk_mq_update_tag_set_shared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_update_tag_set_shared(struct blk_mq_tag_set *set, bool shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815743d0)
Location: block/blk-mq.c:2951
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815743d0-ffffffff8157446f: blk_mq_update_tag_set_shared (STB_LOCAL)
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
In block/blk-mq.c (ffffffff815ddd10)
Location: block/blk-mq.c:3009
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff8168baa0)
Location: block/blk-mq.c:3779
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff8174a170)
Location: block/blk-mq.c:3943
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff8178686c)
Location: block/blk-mq.c:3955
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
In block/blk-mq.c (ffffffff817c8f4c)
Location: block/blk-mq.c:3971
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_exit_queue
  - block/blk-mq.c:blk_mq_init_allocated_queue
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
