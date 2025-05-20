# Function: <code>__traceiter_global_dirty_state</code>

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
int __traceiter_global_dirty_state(void *__data, long unsigned int background_thresh, long unsigned int dirty_thresh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81353820)
Location: include/trace/events/writeback.h:529
Inline: False
```
**Symbols:**

```
ffffffff81353820-ffffffff81353867: __traceiter_global_dirty_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traceiter_global_dirty_state(void *__data, long unsigned int background_thresh, long unsigned int dirty_thresh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135a4f0)
Location: include/trace/events/writeback.h:529
Inline: False
```
**Symbols:**

```
ffffffff8135a4f0-ffffffff8135a535: __traceiter_global_dirty_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traceiter_global_dirty_state(void *__data, long unsigned int background_thresh, long unsigned int dirty_thresh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813a8990)
Location: include/trace/events/writeback.h:530
Inline: False
```
**Symbols:**

```
ffffffff813a8990-ffffffff813a89d5: __traceiter_global_dirty_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traceiter_global_dirty_state(void *__data, long unsigned int background_thresh, long unsigned int dirty_thresh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8142d320)
Location: include/trace/events/writeback.h:530
Inline: False
```
**Symbols:**

```
ffffffff8142d320-ffffffff8142d36f: __traceiter_global_dirty_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traceiter_global_dirty_state(void *__data, long unsigned int background_thresh, long unsigned int dirty_thresh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814babf0)
Location: include/trace/events/writeback.h:530
Inline: False
```
**Symbols:**

```
ffffffff814babf0-ffffffff814bac3f: __traceiter_global_dirty_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traceiter_global_dirty_state(void *__data, long unsigned int background_thresh, long unsigned int dirty_thresh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814efc90)
Location: include/trace/events/writeback.h:530
Inline: False
```
**Symbols:**

```
ffffffff814efc90-ffffffff814efcdf: __traceiter_global_dirty_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traceiter_global_dirty_state(void *__data, long unsigned int background_thresh, long unsigned int dirty_thresh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff815243a0)
Location: include/trace/events/writeback.h:530
Inline: False
```
**Symbols:**

```
ffffffff815243a0-ffffffff815243ef: __traceiter_global_dirty_state (STB_GLOBAL)
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
