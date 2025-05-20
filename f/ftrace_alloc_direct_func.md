# Function: <code>ftrace_alloc_direct_func</code>

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
struct ftrace_direct_func *ftrace_alloc_direct_func(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a9c20)
Location: kernel/trace/ftrace.c:5048
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811a9c20-ffffffff811a9c78: ftrace_alloc_direct_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ftrace_direct_func *ftrace_alloc_direct_func(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aa7e0)
Location: kernel/trace/ftrace.c:5048
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811aa7e0-ffffffff811aa838: ftrace_alloc_direct_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ftrace_direct_func *ftrace_alloc_direct_func(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d4460)
Location: kernel/trace/ftrace.c:5048
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811d4460-ffffffff811d44b8: ftrace_alloc_direct_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ftrace_direct_func *ftrace_alloc_direct_func(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81209220)
Location: kernel/trace/ftrace.c:5214
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff81209220-ffffffff81209282: ftrace_alloc_direct_func (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ftrace_direct_func *ftrace_alloc_direct_func(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81251870)
Location: kernel/trace/ftrace.c:5235
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff81251870-ffffffff812518d2: ftrace_alloc_direct_func (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
