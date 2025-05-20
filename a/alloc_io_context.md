# Function: <code>alloc_io_context</code>

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
struct io_context *alloc_io_context(gfp_t gfp_flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8167d6c0)
Location: block/blk-ioc.c:233
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:__copy_io
  - block/blk-ioc.c:set_task_ioprio
```
**Symbols:**

```
ffffffff8167d6c0-ffffffff8167d74d: alloc_io_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct io_context *alloc_io_context(gfp_t gfp_flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff8173a2a0)
Location: block/blk-ioc.c:233
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:__copy_io
  - block/blk-ioc.c:set_task_ioprio
```
**Symbols:**

```
ffffffff8173a2a0-ffffffff8173a32d: alloc_io_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct io_context *alloc_io_context(gfp_t gfp_flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff817769a0)
Location: block/blk-ioc.c:229
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:__copy_io
  - block/blk-ioc.c:set_task_ioprio
```
**Symbols:**

```
ffffffff817769a0-ffffffff81776a2d: alloc_io_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct io_context *alloc_io_context(gfp_t gfp_flags, int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioc.c (ffffffff817b8bd0)
Location: block/blk-ioc.c:229
Inline: False
Direct callers:
  - block/blk-ioc.c:ioc_find_get_icq
  - block/blk-ioc.c:__copy_io
  - block/blk-ioc.c:set_task_ioprio
```
**Symbols:**

```
ffffffff817b8bd0-ffffffff817b8c5d: alloc_io_context (STB_LOCAL)
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
