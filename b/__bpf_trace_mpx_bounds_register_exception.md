# Function: <code>__bpf_trace_mpx_bounds_register_exception</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_trace_mpx_bounds_register_exception(void *__data, void *addr_referenced, const struct mpx_bndreg *bndreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff810821f0)
Location: arch/x86/include/asm/trace/mpx.h:12
Inline: False
```
**Symbols:**

```
ffffffff810821f0-ffffffff810821fb: __bpf_trace_mpx_bounds_register_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_trace_mpx_bounds_register_exception(void *__data, void *addr_referenced, const struct mpx_bndreg *bndreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff81088e00)
Location: arch/x86/include/asm/trace/mpx.h:12
Inline: False
```
**Symbols:**

```
ffffffff81088e00-ffffffff81088e0b: __bpf_trace_mpx_bounds_register_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_trace_mpx_bounds_register_exception(void *__data, void *addr_referenced, const struct mpx_bndreg *bndreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108c9f0)
Location: arch/x86/include/asm/trace/mpx.h:12
Inline: False
```
**Symbols:**

```
ffffffff8108c9f0-ffffffff8108c9fb: __bpf_trace_mpx_bounds_register_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_trace_mpx_bounds_register_exception(void *__data, void *addr_referenced, const struct mpx_bndreg *bndreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108d650)
Location: arch/x86/include/asm/trace/mpx.h:12
Inline: False
```
**Symbols:**

```
ffffffff8108d650-ffffffff8108d65b: __bpf_trace_mpx_bounds_register_exception (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_trace_mpx_bounds_register_exception(void *__data, void *addr_referenced, const struct mpx_bndreg *bndreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108c610)
Location: arch/x86/include/asm/trace/mpx.h:12
Inline: False
```
**Symbols:**

```
ffffffff8108c610-ffffffff8108c61b: __bpf_trace_mpx_bounds_register_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_trace_mpx_bounds_register_exception(void *__data, void *addr_referenced, const struct mpx_bndreg *bndreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8107b140)
Location: arch/x86/include/asm/trace/mpx.h:12
Inline: False
```
**Symbols:**

```
ffffffff8107b140-ffffffff8107b14b: __bpf_trace_mpx_bounds_register_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_trace_mpx_bounds_register_exception(void *__data, void *addr_referenced, const struct mpx_bndreg *bndreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108c5c0)
Location: arch/x86/include/asm/trace/mpx.h:12
Inline: False
```
**Symbols:**

```
ffffffff8108c5c0-ffffffff8108c5cb: __bpf_trace_mpx_bounds_register_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_trace_mpx_bounds_register_exception(void *__data, void *addr_referenced, const struct mpx_bndreg *bndreg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mpx.c (ffffffff8108e920)
Location: arch/x86/include/asm/trace/mpx.h:12
Inline: False
```
**Symbols:**

```
ffffffff8108e920-ffffffff8108e92b: __bpf_trace_mpx_bounds_register_exception (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
