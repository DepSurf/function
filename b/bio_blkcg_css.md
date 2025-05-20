# Function: <code>bio_blkcg_css</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *bio_blkcg_css(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff816a3ece)
Location: block/blk-cgroup.c:183
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:bio_associate_blkg
Direct callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff816a1100-ffffffff816a112d: bio_blkcg_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *bio_blkcg_css(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81762c1e)
Location: block/blk-cgroup.c:215
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:bio_associate_blkg
Direct callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff8175fd10-ffffffff8175fd3d: bio_blkcg_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *bio_blkcg_css(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817a18ee)
Location: block/blk-cgroup.c:278
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:bio_associate_blkg
Direct callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff8179ebf0-ffffffff8179ec1d: bio_blkcg_css (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct cgroup_subsys_state *bio_blkcg_css(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff817e542e)
Location: block/blk-cgroup.c:278
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
Direct callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - drivers/block/loop.c:loop_queue_rq
```
**Symbols:**

```
ffffffff817e26d0-ffffffff817e26fd: bio_blkcg_css (STB_GLOBAL)
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
