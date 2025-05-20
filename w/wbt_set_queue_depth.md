# Function: <code>wbt_set_queue_depth</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wbt_set_queue_depth(struct rq_wb *rwb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144ac70)
Location: block/blk-wbt.c:655
Inline: False
Direct callers:
  - block/blk-settings.c:blk_set_queue_depth
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff8144ac70-ffffffff8144aca4: wbt_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_queue_depth(struct rq_wb *rwb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814590ad)
Location: block/blk-wbt.c:642
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_set_queue_depth
```
**Symbols:**

```
ffffffff81458ef0-ffffffff81458f22: wbt_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_queue_depth(struct rq_wb *rwb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81484dff)
Location: block/blk-wbt.c:641
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_set_queue_depth
```
**Symbols:**

```
ffffffff81484c50-ffffffff81484c82: wbt_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void wbt_set_queue_depth(struct rq_wb *rwb, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b9ceb)
Location: block/blk-wbt.c:674
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
Direct callers:
  - block/blk-settings.c:blk_set_queue_depth
```
**Symbols:**

```
ffffffff814b9b10-ffffffff814b9b41: wbt_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wbt_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cdc20)
Location: block/blk-wbt.c:631
Inline: False
Direct callers:
  - block/blk-settings.c:blk_set_queue_depth
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814cdc20-ffffffff814cdc57: wbt_set_queue_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wbt_set_queue_depth(struct request_queue *q, unsigned int depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fc4c0)
Location: block/blk-wbt.c:632
Inline: False
Direct callers:
  - block/blk-settings.c:blk_set_queue_depth
  - block/blk-wbt.c:wbt_init
```
**Symbols:**

```
ffffffff814fc4c0-ffffffff814fc4f7: wbt_set_queue_depth (STB_GLOBAL)
```
</details>
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb *rwb</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
