# Function: <code>bpf_get_func_ip_kprobe</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_get_func_ip_kprobe(u64 regs, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81217e10)
Location: kernel/trace/bpf_trace.c:979
Inline: False
```
**Symbols:**

```
ffffffff81217e10-ffffffff81217e22: bpf_get_func_ip_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_get_func_ip_kprobe(u64 regs, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81255c50)
Location: kernel/trace/bpf_trace.c:1029
Inline: False
```
**Symbols:**

```
ffffffff81255c50-ffffffff81255c66: bpf_get_func_ip_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_get_func_ip_kprobe(u64 regs, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a5190)
Location: kernel/trace/bpf_trace.c:1054
Inline: False
```
**Symbols:**

```
ffffffff812a5190-ffffffff812a51b7: bpf_get_func_ip_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_get_func_ip_kprobe(u64 regs, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812c7640)
Location: kernel/trace/bpf_trace.c:1067
Inline: False
```
**Symbols:**

```
ffffffff812c7640-ffffffff812c7667: bpf_get_func_ip_kprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 bpf_get_func_ip_kprobe(u64 regs, u64 __ur_1, u64 __ur_2, u64 __ur_3, u64 __ur_4);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e5947)
Location: kernel/trace/bpf_trace.c:1067
Inline: True
```
**Symbols:**

```
ffffffff821b9646-ffffffff821b965a: bpf_get_func_ip_kprobe.cold (STB_LOCAL)
ffffffff812e58f0-ffffffff812e5971: bpf_get_func_ip_kprobe (STB_GLOBAL)
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
