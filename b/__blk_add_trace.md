# Function: <code>__blk_add_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int rw, u32 what, int error, int pdu_len, void *pdu_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8115bee0)
Location: kernel/trace/blktrace.c:201
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
```
**Symbols:**

```
ffffffff8115bee0-ffffffff8115c24a: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811667d0)
Location: kernel/trace/blktrace.c:203
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
```
**Symbols:**

```
ffffffff811667d0-ffffffff81166b70: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81172080)
Location: kernel/trace/blktrace.c:203
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
```
**Symbols:**

```
ffffffff81172080-ffffffff81172417: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81175480)
Location: kernel/trace/blktrace.c:205
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff81175480-ffffffff811757fa: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81182910)
Location: kernel/trace/blktrace.c:225
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff81182910-ffffffff81182d5d: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81191a90)
Location: kernel/trace/blktrace.c:225
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff81191a90-ffffffff81191eaf: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8119f2c0)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff8119f2c0-ffffffff8119f6df: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811acfd0)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811acfd0-ffffffff811ad42f: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811b8820)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811b8820-ffffffff811b8c7f: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811d1320)
Location: kernel/trace/blktrace.c:215
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811d1320-ffffffff811d1774: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ce720)
Location: kernel/trace/blktrace.c:215
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811ce720-ffffffff811ceb74: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811cfd90)
Location: kernel/trace/blktrace.c:215
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811cfd90-ffffffff811d0166: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:215
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
```
**Symbols:**

```
ffffffff811fc850-ffffffff811fcc62: __blk_add_trace (STB_LOCAL)
ffffffff81cb6117-ffffffff81cb6141: __blk_add_trace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:215
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff81236750-ffffffff81236c49: __blk_add_trace (STB_LOCAL)
ffffffff81e67114-ffffffff81e67147: __blk_add_trace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, const blk_opf_t opf, u32 what, int error, int pdu_len, void *pdu_data, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:215
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff81283430-ffffffff812838ed: __blk_add_trace (STB_LOCAL)
ffffffff8205deed-ffffffff8205df12: __blk_add_trace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, const blk_opf_t opf, u32 what, int error, int pdu_len, void *pdu_data, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:215
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff812a00e0-ffffffff812a0599: __blk_add_trace (STB_LOCAL)
ffffffff820dc98c-ffffffff820dc9b1: __blk_add_trace.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, const blk_opf_t opf, u32 what, int error, int pdu_len, void *pdu_data, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:215
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff812bb810-ffffffff812bbcc9: __blk_add_trace (STB_LOCAL)
ffffffff821b878e-ffffffff821b87b3: __blk_add_trace.cold (STB_LOCAL)
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
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffff800010236fc0)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffff800010236fc0-ffff800010237414: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0472960)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
c0472960-c0472d2c: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0000000002c2bf0)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
c0000000002c2bf0-c0000000002c3090: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffe00018ded8)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffe00018ded8-ffffffe00018e250: __blk_add_trace (STB_LOCAL)
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
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811b0e40)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811b0e40-ffffffff811b129f: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811a3df0)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811a3df0-ffffffff811a423e: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811aec10)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811aec10-ffffffff811af06f: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __blk_add_trace(struct blk_trace *bt, sector_t sector, int bytes, int op, int op_flags, u32 what, int error, int pdu_len, void *pdu_data, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811bcb00)
Location: kernel/trace/blktrace.c:213
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_unplug
  - kernel/trace/blktrace.c:blk_add_trace_plug
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq
```
**Symbols:**

```
ffffffff811bcb00-ffffffff811bcf83: __blk_add_trace (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int op</code>
</li>
<li>
<b>Param added. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int rw</code>
</li>
<li>
<b>Param reordered. </b>
<code>bt, sector, bytes, rw, what, error, pdu_len, pdu_data</code> ➡️ <code>bt, sector, bytes, op, op_flags, what, error, pdu_len, pdu_data</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>union kernfs_node_id *cgid</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>union kernfs_node_id *cgid</code> ➡️ <code>u64 cgid</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const blk_opf_t opf</code>
</li>
<li>
<b>Param removed. </b>
<code>int op</code>
</li>
<li>
<b>Param removed. </b>
<code>int op_flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>bt, sector, bytes, op, op_flags, what, error, pdu_len, pdu_data, cgid</code> ➡️ <code>bt, sector, bytes, opf, what, error, pdu_len, pdu_data, cgid</code>
</li>
</ul>
</details>
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
