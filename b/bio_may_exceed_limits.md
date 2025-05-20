# Function: <code>bio_may_exceed_limits</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8173dad5)
Location: block/blk.h:295
Inline: True
Inline callers:
  - block/blk-merge.c:bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff81747c35)
Location: block/blk.h:295
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff8177a052)
Location: block/blk.h:298
Inline: True
Inline callers:
  - block/blk-merge.c:bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff817842dd)
Location: block/blk.h:298
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-merge.c (ffffffff817bc432)
Location: block/blk.h:296
Inline: True
Inline callers:
  - block/blk-merge.c:bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff817c664c)
Location: block/blk.h:296
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_submit_bio
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
