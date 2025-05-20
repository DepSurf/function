# Function: <code>ext4_es_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/extents_status.h:98
Inline: True
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:98
Inline: True
```
```
In fs/ext4/super.c (ffffffff812dceee)
Location: fs/ext4/extents_status.h:98
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:98
Inline: True
```
```
In fs/ext4/super.c (ffffffff812f2a3c)
Location: fs/ext4/extents_status.h:98
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:98
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:98
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: fs/ext4/extents_status.h:98
Inline: True
```
```
In fs/ext4/super.c (ffffffff8132758a)
Location: fs/ext4/extents_status.h:98
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.h:99
Inline: True
```
```
In fs/ext4/super.c (ffffffff8134ba70)
Location: fs/ext4/extents_status.h:99
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813432b2)
Location: fs/ext4/extents_status.h:99
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff81379876)
Location: fs/ext4/extents_status.h:99
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_delayed_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135aed2)
Location: fs/ext4/extents_status.h:151
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff81392826)
Location: fs/ext4/extents_status.h:151
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81383ef1)
Location: fs/ext4/extents_status.h:151
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813bc6dd)
Location: fs/ext4/extents_status.h:151
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139c9bb)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813d59ad)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e80b3)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff814220b7)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813fa30d)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff81438757)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814006cd)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff8143e907)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81451976)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff81492587)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814ce927)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff81517393)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81567177)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff815b2eb0)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8159f347)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff815e9c10)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d7e97)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:es_do_reclaim_extents
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff81622600)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff80001046f948)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffff8000104b7138)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c062f2d4)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (c0670754)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c00000000058fd70)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (c0000000005de598)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fc37c)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffe00032c7c6)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81394f9b)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813cdf8d)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81385a2b)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813bea0d)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813928fb)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813cb41d)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a6877)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_lookup_extent
  - fs/ext4/extents_status.c:__es_insert_extent
  - fs/ext4/extents_status.c:__es_insert_extent
```
```
In fs/ext4/super.c (ffffffff813e066d)
Location: fs/ext4/extents_status.h:152
Inline: True
Inline callers:
  - fs/ext4/super.c:perf_trace_ext4_es_insert_delayed_block
  - fs/ext4/super.c:perf_trace_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:perf_trace_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:perf_trace_ext4__es_extent
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_insert_delayed_block
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_lookup_extent_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4_es_find_extent_range_exit
  - fs/ext4/super.c:trace_event_raw_event_ext4__es_extent
```
</details>
</li>
</ul>

## Differences
