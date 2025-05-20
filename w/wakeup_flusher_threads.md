# Function: <code>wakeup_flusher_threads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wakeup_flusher_threads(long int nr_pages, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8123c990)
Location: fs/fs-writeback.c:1900
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - fs/sync.c:sys_sync
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff8123c990-ffffffff8123ca75: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wakeup_flusher_threads(long int nr_pages, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812649d0)
Location: fs/fs-writeback.c:1948
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - fs/sync.c:sys_sync
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff812649d0-ffffffff81264b24: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wakeup_flusher_threads(long int nr_pages, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81277e10)
Location: fs/fs-writeback.c:1946
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
  - fs/sync.c:sys_sync
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff81277e10-ffffffff81277f64: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wakeup_flusher_threads(long int nr_pages, enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81285110)
Location: fs/fs-writeback.c:1953
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:sys_sync
  - fs/buffer.c:free_more_memory
```
**Symbols:**

```
ffffffff81285110-ffffffff81285263: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a7c40)
Location: fs/fs-writeback.c:1997
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:sys_sync
```
**Symbols:**

```
ffffffff812a7c40-ffffffff812a7cea: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812ce7d0)
Location: fs/fs-writeback.c:1998
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff812ce7d0-ffffffff812ce86c: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e3b10)
Location: fs/fs-writeback.c:2024
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff812e3b10-ffffffff812e3bdd: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813022b0)
Location: fs/fs-writeback.c:2039
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff813022b0-ffffffff8130237d: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813153c0)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff813153c0-ffffffff81315497: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134ec00)
Location: fs/fs-writeback.c:2135
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8134ec00-ffffffff8134ed36: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135ba80)
Location: fs/fs-writeback.c:2131
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8135ba80-ffffffff8135bbbb: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81362690)
Location: fs/fs-writeback.c:2146
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff81362690-ffffffff813627cb: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813b0e90)
Location: fs/fs-writeback.c:2286
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff813b0e90-ffffffff813b0fcb: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81435d40)
Location: fs/fs-writeback.c:2269
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff81435d40-ffffffff81435e57: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c3d50)
Location: fs/fs-writeback.c:2293
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff814c3d50-ffffffff814c3e03: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f9140)
Location: fs/fs-writeback.c:2304
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff814f9140-ffffffff814f91f3: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152d9a0)
Location: fs/fs-writeback.c:2326
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8152d9a0-ffffffff8152da53: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffff8000103cb620)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffff8000103cb620-ffff8000103cb6d0: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c05a7a34)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
c05a7a34-c05a7adc: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (c0000000004cd2c0)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
c0000000004cd2c0-c0000000004cd3f4: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffe00028947a)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffe00028947a-ffffffe0002894fc: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130d9a0)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8130d9a0-ffffffff8130da77: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812fe5b0)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff812fe5b0-ffffffff812fe687: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8130b790)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8130b790-ffffffff8130b867: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wakeup_flusher_threads(enum wb_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8131cfb0)
Location: fs/fs-writeback.c:2127
Inline: False
Direct callers:
  - mm/page-writeback.c:dirty_writeback_centisecs_handler
  - mm/vmscan.c:shrink_inactive_list
  - fs/sync.c:ksys_sync
```
**Symbols:**

```
ffffffff8131cfb0-ffffffff8131d091: wakeup_flusher_threads (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long int nr_pages</code>
</li>
<li>
<b>Param reordered. </b>
<code>nr_pages, reason</code> ➡️ <code>reason</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
