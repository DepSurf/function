# Function: <code>ftrace_find_direct_func</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_direct_func *ftrace_find_direct_func(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1a2c)
Location: kernel/trace/ftrace.c:4953
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811b2820-ffffffff811b2846: ftrace_find_direct_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_direct_func *ftrace_find_direct_func(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1505)
Location: kernel/trace/ftrace.c:5030
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811b0290-ffffffff811b02b6: ftrace_find_direct_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_direct_func *ftrace_find_direct_func(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b2045)
Location: kernel/trace/ftrace.c:5030
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811b0ba0-ffffffff811b0bc6: ftrace_find_direct_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_direct_func *ftrace_find_direct_func(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811dbf75)
Location: kernel/trace/ftrace.c:5030
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff811daa20-ffffffff811daa46: ftrace_find_direct_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_direct_func *ftrace_find_direct_func(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81211f23)
Location: kernel/trace/ftrace.c:5196
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff81210920-ffffffff81210952: ftrace_find_direct_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct ftrace_direct_func *ftrace_find_direct_func(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125b633)
Location: kernel/trace/ftrace.c:5217
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_direct
```
**Symbols:**

```
ffffffff81259d80-ffffffff81259db2: ftrace_find_direct_func (STB_GLOBAL)
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
