# Function: <code>__blk_mq_alloc_requests</code>

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
struct request *__blk_mq_alloc_requests(struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81683e60)
Location: block/blk-mq.c:440
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff81683e60-ffffffff81684038: __blk_mq_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct request *__blk_mq_alloc_requests(struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817414c0)
Location: block/blk-mq.c:471
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff817414c0-ffffffff81741697: __blk_mq_alloc_requests (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct request *__blk_mq_alloc_requests(struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:435
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_get_new_requests
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff81781790-ffffffff81781b63: __blk_mq_alloc_requests (STB_LOCAL)
ffffffff820f6024-ffffffff820f603d: __blk_mq_alloc_requests.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct request *__blk_mq_alloc_requests(struct blk_mq_alloc_data *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c3dc0)
Location: block/blk-mq.c:437
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_alloc_request
```
**Symbols:**

```
ffffffff817c3dc0-ffffffff817c4042: __blk_mq_alloc_requests (STB_LOCAL)
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
