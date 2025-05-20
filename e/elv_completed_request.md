# Function: <code>elv_completed_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elv_completed_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813b43f0)
Location: block/elevator.c:730
Inline: False
Direct callers:
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff813b43f0-ffffffff813b4439: elv_completed_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elv_completed_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff813f80d0)
Location: block/elevator.c:729
Inline: False
Direct callers:
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff813f80d0-ffffffff813f8127: elv_completed_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elv_completed_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81411af0)
Location: block/elevator.c:727
Inline: False
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff81411af0-ffffffff81411b43: elv_completed_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elv_completed_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141f6b0)
Location: block/elevator.c:785
Inline: False
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff8141f6b0-ffffffff8141f711: elv_completed_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elv_completed_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8144a1d0)
Location: block/elevator.c:802
Inline: False
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff8144a1d0-ffffffff8144a233: elv_completed_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elv_completed_request(struct request_queue *q, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147cf20)
Location: block/elevator.c:771
Inline: False
Direct callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-flush.c:flush_data_end_io
  - block/blk-flush.c:flush_end_io
```
**Symbols:**

```
ffffffff8147cf20-ffffffff8147cf83: elv_completed_request (STB_GLOBAL)
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
