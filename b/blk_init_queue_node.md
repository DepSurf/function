# Function: <code>blk_init_queue_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct request_queue *blk_init_queue_node(request_fn_proc *rfn, spinlock_t *lock, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b9910)
Location: block/blk-core.c:812
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue
```
**Symbols:**

```
ffffffff813b9910-ffffffff813b9970: blk_init_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct request_queue *blk_init_queue_node(request_fn_proc *rfn, spinlock_t *lock, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813fd700)
Location: block/blk-core.c:821
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue
```
**Symbols:**

```
ffffffff813fd700-ffffffff813fd760: blk_init_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct request_queue *blk_init_queue_node(request_fn_proc *rfn, spinlock_t *lock, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81417060)
Location: block/blk-core.c:822
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue
```
**Symbols:**

```
ffffffff81417060-ffffffff814170c0: blk_init_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct request_queue *blk_init_queue_node(request_fn_proc *rfn, spinlock_t *lock, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424d60)
Location: block/blk-core.c:947
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue
```
**Symbols:**

```
ffffffff81424d60-ffffffff81424dbd: blk_init_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct request_queue *blk_init_queue_node(request_fn_proc *rfn, spinlock_t *lock, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144f320)
Location: block/blk-core.c:1025
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue
```
**Symbols:**

```
ffffffff8144f320-ffffffff8144f37d: blk_init_queue_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct request_queue *blk_init_queue_node(request_fn_proc *rfn, spinlock_t *lock, int node_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81482df0)
Location: block/blk-core.c:1139
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_queue
```
**Symbols:**

```
ffffffff81482df0-ffffffff81482e40: blk_init_queue_node (STB_GLOBAL)
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
