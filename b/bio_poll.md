# Function: <code>bio_poll</code>

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
int bio_poll(struct bio *bio, struct io_comp_batch *iob, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679eb0)
Location: block/blk-core.c:917
Inline: False
Direct callers:
  - block/blk-core.c:iocb_bio_iopoll
  - block/blk-mq.c:blk_execute_rq
  - drivers/md/dm.c:dm_poll_bio
```
**Symbols:**

```
ffffffff81679eb0-ffffffff8167a066: bio_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bio_poll(struct bio *bio, struct io_comp_batch *iob, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81736350)
Location: block/blk-core.c:855
Inline: False
Direct callers:
  - block/blk-core.c:iocb_bio_iopoll
  - block/blk-mq.c:blk_execute_rq
  - drivers/md/dm.c:dm_poll_bio
```
**Symbols:**

```
ffffffff81736350-ffffffff8173650b: bio_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bio_poll(struct bio *bio, struct io_comp_batch *iob, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817729b0)
Location: block/blk-core.c:849
Inline: False
Direct callers:
  - block/blk-core.c:iocb_bio_iopoll
  - drivers/md/dm.c:dm_poll_bio
```
**Symbols:**

```
ffffffff817729b0-ffffffff81772b1b: bio_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bio_poll(struct bio *bio, struct io_comp_batch *iob, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b4d50)
Location: block/blk-core.c:884
Inline: False
Direct callers:
  - block/blk-core.c:iocb_bio_iopoll
  - drivers/md/dm.c:dm_poll_bio
```
**Symbols:**

```
ffffffff817b4d50-ffffffff817b4eb5: bio_poll (STB_GLOBAL)
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
