# Function: <code>blk_mq_end_request_batch</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_mq_end_request_batch(struct io_comp_batch *iob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:968
Inline: False
```
**Symbols:**

```
ffffffff81e8ba6a-ffffffff81e8ba94: blk_mq_end_request_batch.cold (STB_LOCAL)
ffffffff816861f0-ffffffff81686709: blk_mq_end_request_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_mq_end_request_batch(struct io_comp_batch *iob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1078
Inline: False
```
**Symbols:**

```
ffffffff8207613b-ffffffff82076171: blk_mq_end_request_batch.cold (STB_LOCAL)
ffffffff81744340-ffffffff81744889: blk_mq_end_request_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_mq_end_request_batch(struct io_comp_batch *iob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1074
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_complete_batch
```
**Symbols:**

```
ffffffff820f5fb4-ffffffff820f5fde: blk_mq_end_request_batch.cold (STB_LOCAL)
ffffffff8177fd60-ffffffff81780251: blk_mq_end_request_batch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_end_request_batch(struct io_comp_batch *iob);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1079
Inline: False
Direct callers:
  - drivers/block/virtio_blk.c:virtblk_complete_batch
```
**Symbols:**

```
ffffffff821d33c9-ffffffff821d33f3: blk_mq_end_request_batch.cold (STB_LOCAL)
ffffffff817c15a0-ffffffff817c1aa1: blk_mq_end_request_batch (STB_GLOBAL)
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
