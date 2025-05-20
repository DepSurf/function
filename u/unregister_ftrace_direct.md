# Function: <code>unregister_ftrace_direct</code>

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
int unregister_ftrace_direct(long unsigned int ip, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1970)
Location: kernel/trace/ftrace.c:5124
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff811b1970-ffffffff811b1b57: unregister_ftrace_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unregister_ftrace_direct(long unsigned int ip, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811af3e0)
Location: kernel/trace/ftrace.c:5211
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff811af3e0-ffffffff811af5c7: unregister_ftrace_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unregister_ftrace_direct(long unsigned int ip, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811afc40)
Location: kernel/trace/ftrace.c:5211
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff811afc40-ffffffff811afe27: unregister_ftrace_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unregister_ftrace_direct(long unsigned int ip, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811d9ad0)
Location: kernel/trace/ftrace.c:5211
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff811d9ad0-ffffffff811d9cb7: unregister_ftrace_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unregister_ftrace_direct(long unsigned int ip, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8120f350)
Location: kernel/trace/ftrace.c:5358
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8120f350-ffffffff8120f58e: unregister_ftrace_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unregister_ftrace_direct(long unsigned int ip, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812586c0)
Location: kernel/trace/ftrace.c:5381
Inline: False
```
**Symbols:**

```
ffffffff812586c0-ffffffff812588ca: unregister_ftrace_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unregister_ftrace_direct(struct ftrace_ops *ops, long unsigned int addr, bool free_filters);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126e620)
Location: kernel/trace/ftrace.c:5485
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff8126e620-ffffffff8126e6e1: unregister_ftrace_direct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_direct(struct ftrace_ops *ops, long unsigned int addr, bool free_filters);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:5489
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
```
**Symbols:**

```
ffffffff821b74d7-ffffffff821b752c: unregister_ftrace_direct.cold (STB_LOCAL)
ffffffff81288b00-ffffffff81288cdf: unregister_ftrace_direct (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct ftrace_ops *ops</code>
</li>
<li>
<b>Param added. </b>
<code>bool free_filters</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int ip</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
