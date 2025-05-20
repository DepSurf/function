# Function: <code>elv_set_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int elv_set_request(struct request_queue *q, struct request *rq, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b4360)
Location: block/elevator.c:702
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff813b4360-ffffffff813b4381: elv_set_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int elv_set_request(struct request_queue *q, struct request *rq, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f8040)
Location: block/elevator.c:701
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff813f8040-ffffffff813f8064: elv_set_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int elv_set_request(struct request_queue *q, struct request *rq, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411a60)
Location: block/elevator.c:699
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff81411a60-ffffffff81411a84: elv_set_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int elv_set_request(struct request_queue *q, struct request *rq, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f620)
Location: block/elevator.c:748
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff8141f620-ffffffff8141f64e: elv_set_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int elv_set_request(struct request_queue *q, struct request *rq, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8144a120)
Location: block/elevator.c:765
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff8144a120-ffffffff8144a153: elv_set_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int elv_set_request(struct request_queue *q, struct request *rq, struct bio *bio, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147ce70)
Location: block/elevator.c:734
Inline: False
Direct callers:
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
**Symbols:**

```
ffffffff8147ce70-ffffffff8147cea1: elv_set_request (STB_GLOBAL)
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
