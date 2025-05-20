# Function: <code>__ftrace_hash_move</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811561a0)
Location: kernel/trace/ftrace.c:1462
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811561a0-ffffffff811562ce: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81162cc0)
Location: kernel/trace/ftrace.c:1438
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff81162cc0-ffffffff81162dee: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81171b40)
Location: kernel/trace/ftrace.c:1427
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff81171b40-ffffffff81171c6e: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117f350)
Location: kernel/trace/ftrace.c:1376
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff8117f350-ffffffff8117f47e: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118c450)
Location: kernel/trace/ftrace.c:1373
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff8118c450-ffffffff8118c555: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81198020)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff81198020-ffffffff81198125: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0f97)
Location: kernel/trace/ftrace.c:1398
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aea07)
Location: kernel/trace/ftrace.c:1397
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af3b7)
Location: kernel/trace/ftrace.c:1397
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d91f7)
Location: kernel/trace/ftrace.c:1398
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120ff23)
Location: kernel/trace/ftrace.c:1392
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81259303)
Location: kernel/trace/ftrace.c:1398
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812706d3)
Location: kernel/trace/ftrace.c:1429
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:1428
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff81284fb0-ffffffff8128510b: __ftrace_hash_move (STB_LOCAL)
ffffffff821b731e-ffffffff821b7383: __ftrace_hash_move.cold (STB_LOCAL)
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
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010210798)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffff800010210798-ffff8000102108d0: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044f6ec)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
c044f6ec-c044f81c: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0000000002901b0)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
c0000000002901b0-c000000000290388: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000171340)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffe000171340-ffffffe000171432: __ftrace_hash_move (STB_LOCAL)
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
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81190640)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff81190640-ffffffff81190745: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811839d0)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff811839d0-ffffffff81183ad5: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118e410)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff8118e410-ffffffff8118e515: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ftrace_hash *__ftrace_hash_move(struct ftrace_hash *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119bfa0)
Location: kernel/trace/ftrace.c:1374
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_graph_release
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
  - kernel/trace/ftrace.c:ftrace_hash_move_and_update_ops
```
**Symbols:**

```
ffffffff8119bfa0-ffffffff8119c0a5: __ftrace_hash_move (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
