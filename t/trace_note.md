# Function: <code>trace_note</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8115bd60)
Location: kernel/trace/blktrace.c:68
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:blk_trace_startstop
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff8115bd60-ffffffff8115bed4: trace_note.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81166650)
Location: kernel/trace/blktrace.c:68
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff81166650-ffffffff811667c5: trace_note.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81171ef0)
Location: kernel/trace/blktrace.c:68
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff81171ef0-ffffffff8117207a: trace_note.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811752f0)
Location: kernel/trace/blktrace.c:70
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811752f0-ffffffff8117547c: trace_note.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811826c0)
Location: kernel/trace/blktrace.c:78
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811826c0-ffffffff8118290f: trace_note.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff81191850)
Location: kernel/trace/blktrace.c:78
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff81191850-ffffffff81191a83: trace_note.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff8119f080)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff8119f080-ffffffff8119f2b3: trace_note.isra.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811acd80)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811acd80-ffffffff811acfc5: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811b85d0)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811b85d0-ffffffff811b8815: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811d10c0)
Location: kernel/trace/blktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811d10c0-ffffffff811d1319: trace_note (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ce4c0)
Location: kernel/trace/blktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811ce4c0-ffffffff811ce719: trace_note (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ceec0)
Location: kernel/trace/blktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811ceec0-ffffffff811cf096: trace_note (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811fc1c0-ffffffff811fc391: trace_note (STB_LOCAL)
ffffffff81cb60dd-ffffffff81cb60fa: trace_note.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/trace/blktrace.c:trace_note_time
```
**Symbols:**

```
ffffffff81236520-ffffffff8123674a: trace_note (STB_LOCAL)
ffffffff81e670f7-ffffffff81e67114: trace_note.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/trace/blktrace.c:trace_note_time
```
**Symbols:**

```
ffffffff812831f0-ffffffff8128341a: trace_note (STB_LOCAL)
ffffffff8205ded0-ffffffff8205deed: trace_note.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/trace/blktrace.c:trace_note_time
```
**Symbols:**

```
ffffffff8129fea0-ffffffff812a00ca: trace_note (STB_LOCAL)
ffffffff820dc96f-ffffffff820dc98c: trace_note.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, u64 cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (0)
Location: kernel/trace/blktrace.c:69
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__blk_trace_note_message
  - kernel/trace/blktrace.c:trace_note_time
```
**Symbols:**

```
ffffffff812bb5d0-ffffffff812bb7fa: trace_note (STB_LOCAL)
ffffffff821b8771-ffffffff821b878e: trace_note.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffff800010236368)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffff800010236368-ffff800010236574: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_note(struct blk_trace *bt, pid_t pid, int action, const void *data, size_t len, union kernfs_node_id *cgid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/blktrace.c (c0472620)
Location: kernel/trace/blktrace.c:66
Inline: False
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
c0472620-c0472800: trace_note (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (c0000000002c2760)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
c0000000002c2760-c0000000002c29f4: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffe00018dbc2)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_trace_startstop
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffe00018dbc2-ffffffe00018dd9a: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811b0bf0)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811b0bf0-ffffffff811b0e35: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811a3a40)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811a3a40-ffffffff811a3c85: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811ae9c0)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811ae9c0-ffffffff811aec05: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/blktrace.c (ffffffff811bc890)
Location: kernel/trace/blktrace.c:66
Inline: True
Direct callers:
  - kernel/trace/blktrace.c:__blk_add_trace
  - kernel/trace/blktrace.c:__trace_note_message
```
**Symbols:**

```
ffffffff811bc890-ffffffff811bcaf5: trace_note.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
