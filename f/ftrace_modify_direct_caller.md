# Function: <code>ftrace_modify_direct_caller</code>

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
int ftrace_modify_direct_caller(struct ftrace_func_entry *entry, struct dyn_ftrace *rec, long unsigned int old_addr, long unsigned int new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b3770)
Location: kernel/trace/ftrace.c:5187
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
```
**Symbols:**

```
ffffffff811b3770-ffffffff811b38c4: ftrace_modify_direct_caller (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ftrace_modify_direct_caller(struct ftrace_func_entry *entry, struct dyn_ftrace *rec, long unsigned int old_addr, long unsigned int new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1340)
Location: kernel/trace/ftrace.c:5274
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct
```
**Symbols:**

```
ffffffff811b1340-ffffffff811b1494: ftrace_modify_direct_caller (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ftrace_modify_direct_caller(struct ftrace_func_entry *entry, struct dyn_ftrace *rec, long unsigned int old_addr, long unsigned int new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1e80)
Location: kernel/trace/ftrace.c:5274
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct
```
**Symbols:**

```
ffffffff811b1e80-ffffffff811b1fd4: ftrace_modify_direct_caller (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ftrace_modify_direct_caller(struct ftrace_func_entry *entry, struct dyn_ftrace *rec, long unsigned int old_addr, long unsigned int new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811dbdb0)
Location: kernel/trace/ftrace.c:5274
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct
```
**Symbols:**

```
ffffffff811dbdb0-ffffffff811dbf04: ftrace_modify_direct_caller (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ftrace_modify_direct_caller(struct ftrace_func_entry *entry, struct dyn_ftrace *rec, long unsigned int old_addr, long unsigned int new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81211d40)
Location: kernel/trace/ftrace.c:5427
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct
```
**Symbols:**

```
ffffffff81211d40-ffffffff81211e96: ftrace_modify_direct_caller (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_modify_direct_caller(struct ftrace_func_entry *entry, struct dyn_ftrace *rec, long unsigned int old_addr, long unsigned int new_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125b480)
Location: kernel/trace/ftrace.c:5452
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct
```
**Symbols:**

```
ffffffff8125b480-ffffffff8125b59f: ftrace_modify_direct_caller (STB_WEAK)
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
