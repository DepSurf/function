# Function: <code>__bpf_trace_hugepage_update</code>

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
void __bpf_trace_hugepage_update(void *__data, long unsigned int addr, long unsigned int pte, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813b8eb0)
Location: include/trace/events/thp.h:29
Inline: False
```
**Symbols:**

```
ffffffff813b8eb0-ffffffff813b8eca: __bpf_trace_hugepage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_trace_hugepage_update(void *__data, long unsigned int addr, long unsigned int pte, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143b0a0)
Location: include/trace/events/thp.h:29
Inline: False
```
**Symbols:**

```
ffffffff8143b0a0-ffffffff8143b0ba: __bpf_trace_hugepage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_trace_hugepage_update(void *__data, long unsigned int addr, long unsigned int pte, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814709f0)
Location: include/trace/events/thp.h:29
Inline: False
```
**Symbols:**

```
ffffffff814709f0-ffffffff81470a0a: __bpf_trace_hugepage_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_trace_hugepage_update(void *__data, long unsigned int addr, long unsigned int pte, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8149fdb0)
Location: include/trace/events/thp.h:38
Inline: False
```
**Symbols:**

```
ffffffff8149fdb0-ffffffff8149fdca: __bpf_trace_hugepage_update (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_trace_hugepage_update(void *__data, long unsigned int addr, long unsigned int pte, long unsigned int clr, long unsigned int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/book3s64/hash_pgtable.c (c00000000008b1d0)
Location: include/trace/events/thp.h:47
Inline: False
```
**Symbols:**

```
c00000000008b1d0-c00000000008b1fc: __bpf_trace_hugepage_update (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
