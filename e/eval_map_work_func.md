# Function: <code>eval_map_work_func</code>

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
void eval_map_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff82fe2105)
Location: kernel/trace/trace.c:9076
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff82fe2105-ffffffff82fe212e: eval_map_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void eval_map_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff831ec69d)
Location: kernel/trace/trace.c:9415
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff831ec69d-ffffffff831ec6c7: eval_map_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void eval_map_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff832d116d)
Location: kernel/trace/trace.c:9577
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff832d116d-ffffffff832d1197: eval_map_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void eval_map_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff834852b4)
Location: kernel/trace/trace.c:9611
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_eval_init
```
**Symbols:**

```
ffffffff834852b4-ffffffff834852f2: eval_map_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void eval_map_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb3e63)
Location: kernel/trace/trace.c:9704
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_eval_init
```
**Symbols:**

```
ffffffff83eb3d90-ffffffff83eb3dce: eval_map_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void eval_map_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff836d9193)
Location: kernel/trace/trace.c:9869
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_eval_init
```
**Symbols:**

```
ffffffff836d90c0-ffffffff836d90fe: eval_map_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void eval_map_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390b723)
Location: kernel/trace/trace.c:10064
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_eval_init
```
**Symbols:**

```
ffffffff8390b650-ffffffff8390b68e: eval_map_work_func (STB_LOCAL)
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
