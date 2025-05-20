# Function: <code>ftrace_lookup_symbols</code>

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
int ftrace_lookup_symbols(const char **sorted_syms, size_t cnt, long unsigned int *addrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81213120)
Location: kernel/trace/ftrace.c:8078
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:get_ftrace_locations
```
**Symbols:**

```
ffffffff81213120-ffffffff812131b8: ftrace_lookup_symbols (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_lookup_symbols(const char **sorted_syms, size_t cnt, long unsigned int *addrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125c910)
Location: kernel/trace/ftrace.c:8334
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:register_fprobe_syms
```
**Symbols:**

```
ffffffff8125c910-ffffffff8125c9b3: ftrace_lookup_symbols (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ftrace_lookup_symbols(const char **sorted_syms, size_t cnt, long unsigned int *addrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81273850)
Location: kernel/trace/ftrace.c:8148
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:register_fprobe_syms
```
**Symbols:**

```
ffffffff81273850-ffffffff812738f5: ftrace_lookup_symbols (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ftrace_lookup_symbols(const char **sorted_syms, size_t cnt, long unsigned int *addrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128dde0)
Location: kernel/trace/ftrace.c:8148
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/fprobe.c:get_ftrace_locations
```
**Symbols:**

```
ffffffff8128dde0-ffffffff8128de85: ftrace_lookup_symbols (STB_GLOBAL)
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
