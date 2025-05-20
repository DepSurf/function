# Function: <code>bpf_jit_stack_offsetof</code>

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
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bpf_jit_stack_offsetof(struct codegen_context *ctx, int reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/net/bpf_jit_comp64.c (c000000000104c60)
Location: arch/powerpc/net/bpf_jit_comp64.c:77
Inline: True
Direct callers:
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_emit_common_epilogue
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_emit_common_epilogue
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_emit_common_epilogue
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_build_prologue
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_build_prologue
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_build_prologue
```
**Symbols:**

```
c000000000104c60-c000000000104cc8: bpf_jit_stack_offsetof (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
