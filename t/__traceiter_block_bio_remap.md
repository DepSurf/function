# Function: <code>__traceiter_block_bio_remap</code>

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
int __traceiter_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155daf0)
Location: include/trace/events/block.h:456
Inline: False
```
**Symbols:**

```
ffffffff8155daf0-ffffffff8155db41: __traceiter_block_bio_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81566370)
Location: include/trace/events/block.h:456
Inline: False
```
**Symbols:**

```
ffffffff81566370-ffffffff815663bf: __traceiter_block_bio_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815ca740)
Location: include/trace/events/block.h:456
Inline: False
```
**Symbols:**

```
ffffffff815ca740-ffffffff815ca78f: __traceiter_block_bio_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81675ca0)
Location: include/trace/events/block.h:479
Inline: False
```
**Symbols:**

```
ffffffff81675ca0-ffffffff81675cfb: __traceiter_block_bio_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81731c40)
Location: include/trace/events/block.h:479
Inline: False
```
**Symbols:**

```
ffffffff81731c40-ffffffff81731c9b: __traceiter_block_bio_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8176dfa0)
Location: include/trace/events/block.h:505
Inline: False
```
**Symbols:**

```
ffffffff8176dfa0-ffffffff8176dffb: __traceiter_block_bio_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_block_bio_remap(void *__data, struct bio *bio, dev_t dev, sector_t from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff817b01d0)
Location: include/trace/events/block.h:507
Inline: False
```
**Symbols:**

```
ffffffff817b01d0-ffffffff817b022b: __traceiter_block_bio_remap (STB_GLOBAL)
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
