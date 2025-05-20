# Function: <code>__blk_mq_alloc_requests_batch</code>

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
struct request *__blk_mq_alloc_requests_batch(struct blk_mq_alloc_data *data, u64 alloc_time_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:409
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_requests
```
**Symbols:**

```
ffffffff816838f0-ffffffff81683a49: __blk_mq_alloc_requests_batch (STB_LOCAL)
ffffffff81e8b74f-ffffffff81e8b7b2: __blk_mq_alloc_requests_batch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct request *__blk_mq_alloc_requests_batch(struct blk_mq_alloc_data *data, u64 alloc_time_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:440
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_requests
```
**Symbols:**

```
ffffffff81741270-ffffffff817413c9: __blk_mq_alloc_requests_batch (STB_LOCAL)
ffffffff82075ee8-ffffffff82075f4b: __blk_mq_alloc_requests_batch.cold (STB_LOCAL)
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
In block/blk-mq.c (ffffffff817818cb)
Location: block/blk-mq.c:405
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_alloc_requests
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct request *__blk_mq_alloc_requests_batch(struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:405
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_alloc_requests
```
**Symbols:**

```
ffffffff817bfea0-ffffffff817c003e: __blk_mq_alloc_requests_batch (STB_LOCAL)
ffffffff821d33b0-ffffffff821d33c9: __blk_mq_alloc_requests_batch.cold (STB_LOCAL)
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
</ul>
