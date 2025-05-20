# Function: <code>timens_for_children_get</code>

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
struct ns_common *timens_for_children_get(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81159df0)
Location: kernel/time/namespace.c:262
Inline: False
Direct callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
```
**Symbols:**

```
ffffffff81159df0-ffffffff81159e74: timens_for_children_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ns_common *timens_for_children_get(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81155dd0)
Location: kernel/time/namespace.c:259
Inline: False
Direct callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
```
**Symbols:**

```
ffffffff81155dd0-ffffffff81155e54: timens_for_children_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ns_common *timens_for_children_get(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff81156fe0)
Location: kernel/time/namespace.c:259
Inline: False
Direct callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
```
**Symbols:**

```
ffffffff81156fe0-ffffffff81157064: timens_for_children_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ns_common *timens_for_children_get(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8117be30)
Location: kernel/time/namespace.c:259
Inline: False
Direct callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
```
**Symbols:**

```
ffffffff8117be30-ffffffff8117beb4: timens_for_children_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ns_common *timens_for_children_get(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811b1f5e)
Location: kernel/time/namespace.c:259
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
```
**Symbols:**

```
ffffffff811b15f0-ffffffff811b167b: timens_for_children_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ns_common *timens_for_children_get(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff811f2d8e)
Location: kernel/time/namespace.c:277
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
```
**Symbols:**

```
ffffffff811f2320-ffffffff811f23ab: timens_for_children_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct ns_common *timens_for_children_get(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8120750e)
Location: kernel/time/namespace.c:277
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
```
**Symbols:**

```
ffffffff81206ab0-ffffffff81206b3b: timens_for_children_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ns_common *timens_for_children_get(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/namespace.c (ffffffff8121e71e)
Location: kernel/time/namespace.c:277
Inline: True
Inline callers:
  - kernel/time/namespace.c:proc_timens_set_offset
  - kernel/time/namespace.c:proc_timens_show_offsets
```
**Symbols:**

```
ffffffff8121dcc0-ffffffff8121dd4b: timens_for_children_get (STB_LOCAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
