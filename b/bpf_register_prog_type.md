# Function: <code>bpf_register_prog_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_register_prog_type(struct bpf_prog_type_list *tl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811734f0)
Location: kernel/bpf/syscall.c:438
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:register_kprobe_prog_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
```
**Symbols:**

```
ffffffff811734f0-ffffffff81173518: bpf_register_prog_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bpf_register_prog_type(struct bpf_prog_type_list *tl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81181700)
Location: kernel/bpf/syscall.c:535
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:register_kprobe_prog_ops
  - kernel/trace/bpf_trace.c:register_kprobe_prog_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
```
**Symbols:**

```
ffffffff81181700-ffffffff81181728: bpf_register_prog_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_register_prog_type(struct bpf_prog_type_list *tl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118d340)
Location: kernel/bpf/syscall.c:576
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:register_kprobe_prog_ops
  - kernel/trace/bpf_trace.c:register_kprobe_prog_ops
  - kernel/trace/bpf_trace.c:register_kprobe_prog_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
  - net/core/filter.c:register_sk_filter_ops
```
**Symbols:**

```
ffffffff8118d340-ffffffff8118d368: bpf_register_prog_type (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
