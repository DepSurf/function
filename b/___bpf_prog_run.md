# Function: <code>___bpf_prog_run</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int ___bpf_prog_run(u64 *regs, const struct bpf_insn *insn, u64 *stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118fd40)
Location: kernel/bpf/core.c:766
Inline: False
Direct callers:
  - kernel/bpf/core.c:__bpf_prog_run512
  - kernel/bpf/core.c:__bpf_prog_run480
  - kernel/bpf/core.c:__bpf_prog_run448
  - kernel/bpf/core.c:__bpf_prog_run416
  - kernel/bpf/core.c:__bpf_prog_run384
  - kernel/bpf/core.c:__bpf_prog_run352
  - kernel/bpf/core.c:__bpf_prog_run320
  - kernel/bpf/core.c:__bpf_prog_run288
  - kernel/bpf/core.c:__bpf_prog_run256
  - kernel/bpf/core.c:__bpf_prog_run224
  - kernel/bpf/core.c:__bpf_prog_run192
  - kernel/bpf/core.c:__bpf_prog_run160
  - kernel/bpf/core.c:__bpf_prog_run128
  - kernel/bpf/core.c:__bpf_prog_run96
  - kernel/bpf/core.c:__bpf_prog_run64
  - kernel/bpf/core.c:__bpf_prog_run32
```
**Symbols:**

```
ffffffff8118fd40-ffffffff81190f15: ___bpf_prog_run (STB_LOCAL)
```
</details>
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
</ul>
