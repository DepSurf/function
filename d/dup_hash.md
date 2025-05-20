# Function: <code>dup_hash</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ftrace_hash *dup_hash(struct ftrace_hash *src, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811adcd0)
Location: kernel/trace/ftrace.c:1361
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811adcd0-ffffffff811addd3: dup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ftrace_hash *dup_hash(struct ftrace_hash *src, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ab5e0)
Location: kernel/trace/ftrace.c:1360
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811ab5e0-ffffffff811ab6e2: dup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ftrace_hash *dup_hash(struct ftrace_hash *src, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac070)
Location: kernel/trace/ftrace.c:1360
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811ac070-ffffffff811ac175: dup_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ftrace_hash *dup_hash(struct ftrace_hash *src, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1361
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811d5d20-ffffffff811d5e4b: dup_hash (STB_LOCAL)
ffffffff81cb42f1-ffffffff81cb4356: dup_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ftrace_hash *dup_hash(struct ftrace_hash *src, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1355
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_add_rec_direct
```
**Symbols:**

```
ffffffff8120af20-ffffffff8120b063: dup_hash (STB_LOCAL)
ffffffff81e652c2-ffffffff81e65327: dup_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ftrace_hash *dup_hash(struct ftrace_hash *src, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1361
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_add_rec_direct
```
**Symbols:**

```
ffffffff81253860-ffffffff812539a3: dup_hash (STB_LOCAL)
ffffffff8205cc9a-ffffffff8205ccff: dup_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ftrace_hash *dup_hash(struct ftrace_hash *src, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1392
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff8126ac80-ffffffff8126adc3: dup_hash (STB_LOCAL)
ffffffff820db5d9-ffffffff820db63e: dup_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81285009)
Location: kernel/trace/ftrace.c:1391
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:__ftrace_hash_move
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
</ul>
