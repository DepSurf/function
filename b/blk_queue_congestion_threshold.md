# Function: <code>blk_queue_congestion_threshold</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_congestion_threshold(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9710)
Location: block/blk-core.c:91
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_nr_requests
Direct callers:
  - block/blk-settings.c:blk_queue_make_request
```
**Symbols:**

```
ffffffff813b9710-ffffffff813b975a: blk_queue_congestion_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_congestion_threshold(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fdccc)
Location: block/blk-core.c:91
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_nr_requests
Direct callers:
  - block/blk-settings.c:blk_queue_make_request
```
**Symbols:**

```
ffffffff813fd4d0-ffffffff813fd51a: blk_queue_congestion_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_congestion_threshold(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8141760c)
Location: block/blk-core.c:92
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_nr_requests
Direct callers:
  - block/blk-settings.c:blk_queue_make_request
```
**Symbols:**

```
ffffffff81416e20-ffffffff81416e6a: blk_queue_congestion_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_congestion_threshold(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8142547b)
Location: block/blk-core.c:98
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_nr_requests
Direct callers:
  - block/blk-settings.c:blk_queue_make_request
```
**Symbols:**

```
ffffffff81424ac0-ffffffff81424b0a: blk_queue_congestion_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_congestion_threshold(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8145061b)
Location: block/blk-core.c:98
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_nr_requests
Direct callers:
  - block/blk-settings.c:blk_queue_make_request
```
**Symbols:**

```
ffffffff8144fba0-ffffffff8144fbea: blk_queue_congestion_threshold (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_queue_congestion_threshold(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81483920)
Location: block/blk-core.c:171
Inline: True
Inline callers:
  - block/blk-core.c:blk_update_nr_requests
Direct callers:
  - block/blk-settings.c:blk_queue_make_request
```
**Symbols:**

```
ffffffff81482ba0-ffffffff81482bea: blk_queue_congestion_threshold (STB_GLOBAL)
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
