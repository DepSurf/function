# Function: <code>__traceiter_bdi_dirty_ratelimit</code>

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
int __traceiter_bdi_dirty_ratelimit(void *__data, struct bdi_writeback *wb, long unsigned int dirty_rate, long unsigned int task_ratelimit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81353870)
Location: include/trace/events/writeback.h:574
Inline: False
```
**Symbols:**

```
ffffffff81353870-ffffffff813538c1: __traceiter_bdi_dirty_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_bdi_dirty_ratelimit(void *__data, struct bdi_writeback *wb, long unsigned int dirty_rate, long unsigned int task_ratelimit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135a540)
Location: include/trace/events/writeback.h:574
Inline: False
```
**Symbols:**

```
ffffffff8135a540-ffffffff8135a58f: __traceiter_bdi_dirty_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_bdi_dirty_ratelimit(void *__data, struct bdi_writeback *wb, long unsigned int dirty_rate, long unsigned int task_ratelimit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813a89e0)
Location: include/trace/events/writeback.h:575
Inline: False
```
**Symbols:**

```
ffffffff813a89e0-ffffffff813a8a2f: __traceiter_bdi_dirty_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_bdi_dirty_ratelimit(void *__data, struct bdi_writeback *wb, long unsigned int dirty_rate, long unsigned int task_ratelimit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8142d370)
Location: include/trace/events/writeback.h:575
Inline: False
```
**Symbols:**

```
ffffffff8142d370-ffffffff8142d3cb: __traceiter_bdi_dirty_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_bdi_dirty_ratelimit(void *__data, struct bdi_writeback *wb, long unsigned int dirty_rate, long unsigned int task_ratelimit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814bac50)
Location: include/trace/events/writeback.h:575
Inline: False
```
**Symbols:**

```
ffffffff814bac50-ffffffff814bacab: __traceiter_bdi_dirty_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_bdi_dirty_ratelimit(void *__data, struct bdi_writeback *wb, long unsigned int dirty_rate, long unsigned int task_ratelimit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814efd10)
Location: include/trace/events/writeback.h:575
Inline: False
```
**Symbols:**

```
ffffffff814efd10-ffffffff814efd6b: __traceiter_bdi_dirty_ratelimit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_bdi_dirty_ratelimit(void *__data, struct bdi_writeback *wb, long unsigned int dirty_rate, long unsigned int task_ratelimit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81524420)
Location: include/trace/events/writeback.h:575
Inline: False
```
**Symbols:**

```
ffffffff81524420-ffffffff8152447b: __traceiter_bdi_dirty_ratelimit (STB_GLOBAL)
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
