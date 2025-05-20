# Function: <code>ftrace_add_rec_direct</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *ftrace_add_rec_direct(long unsigned int ip, long unsigned int addr, struct ftrace_hash **free_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:2410
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff8120b070-ffffffff8120b15c: ftrace_add_rec_direct (STB_LOCAL)
ffffffff81e65327-ffffffff81e6534c: ftrace_add_rec_direct.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *ftrace_add_rec_direct(long unsigned int ip, long unsigned int addr, struct ftrace_hash **free_hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:2461
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff812539c0-ffffffff81253aac: ftrace_add_rec_direct (STB_LOCAL)
ffffffff8205ccff-ffffffff8205cd24: ftrace_add_rec_direct.cold (STB_LOCAL)
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
In kernel/trace/ftrace.c (ffffffff81272ec9)
Location: kernel/trace/ftrace.c:2559
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_direct
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
