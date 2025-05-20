# Function: <code>tracer_init_tracefs_work_func</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tracer_init_tracefs_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83485aac)
Location: kernel/trace/trace.c:9719
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff83485aac-ffffffff83485cce: tracer_init_tracefs_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tracer_init_tracefs_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb3ef0)
Location: kernel/trace/trace.c:9812
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff83eb3ef0-ffffffff83eb423a: tracer_init_tracefs_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tracer_init_tracefs_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff836d9220)
Location: kernel/trace/trace.c:9977
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff836d9220-ffffffff836d956a: tracer_init_tracefs_work_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tracer_init_tracefs_work_func(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390b7b0)
Location: kernel/trace/trace.c:10172
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_init_tracefs
```
**Symbols:**

```
ffffffff8390b7b0-ffffffff8390bafa: tracer_init_tracefs_work_func (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
