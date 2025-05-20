# Function: <code>find_direct_entry</code>

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
struct ftrace_func_entry *find_direct_entry(long unsigned int *ip, struct dyn_ftrace **recp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ac5d0)
Location: kernel/trace/ftrace.c:5097
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
```
**Symbols:**

```
ffffffff811ac5d0-ffffffff811ac663: find_direct_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ftrace_func_entry *find_direct_entry(long unsigned int *ip, struct dyn_ftrace **recp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a9ee0)
Location: kernel/trace/ftrace.c:5184
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
```
**Symbols:**

```
ffffffff811a9ee0-ffffffff811a9f73: find_direct_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ftrace_func_entry *find_direct_entry(long unsigned int *ip, struct dyn_ftrace **recp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aaaa0)
Location: kernel/trace/ftrace.c:5184
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
```
**Symbols:**

```
ffffffff811aaaa0-ffffffff811aab37: find_direct_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *find_direct_entry(long unsigned int *ip, struct dyn_ftrace **recp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5184
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
```
**Symbols:**

```
ffffffff811d4710-ffffffff811d47d1: find_direct_entry (STB_LOCAL)
ffffffff81cb40ad-ffffffff81cb40d1: find_direct_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *find_direct_entry(long unsigned int *ip, struct dyn_ftrace **recp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5331
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
```
**Symbols:**

```
ffffffff81209500-ffffffff812095c0: find_direct_entry (STB_LOCAL)
ffffffff81e65040-ffffffff81e65064: find_direct_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ftrace_func_entry *find_direct_entry(long unsigned int *ip, struct dyn_ftrace **recp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5354
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
```
**Symbols:**

```
ffffffff81251ba0-ffffffff81251c60: find_direct_entry (STB_LOCAL)
ffffffff8205cb33-ffffffff8205cb57: find_direct_entry.cold (STB_LOCAL)
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
</ul>
