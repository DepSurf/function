# Function: <code>arch_prepare_bpf_trampoline</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int arch_prepare_bpf_trampoline(void *image, void *image_end, const struct btf_func_model *m, u32 flags, struct bpf_tramp_progs *tprogs, void *orig_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8121f230)
Location: arch/x86/net/bpf_jit_comp.c:1574
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810a32c8-ffffffff810a32f7: arch_prepare_bpf_trampoline.cold (STB_LOCAL)
ffffffff810a2800-ffffffff810a2d5c: arch_prepare_bpf_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int arch_prepare_bpf_trampoline(struct bpf_tramp_image *im, void *image, void *image_end, const struct btf_func_model *m, u32 flags, struct bpf_tramp_progs *tprogs, void *orig_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81222bb0)
Location: arch/x86/net/bpf_jit_comp.c:1747
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81bdafbe-ffffffff81bdb02f: arch_prepare_bpf_trampoline.cold (STB_LOCAL)
ffffffff8109e120-ffffffff8109e74a: arch_prepare_bpf_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int arch_prepare_bpf_trampoline(struct bpf_tramp_image *im, void *image, void *image_end, const struct btf_func_model *m, u32 flags, struct bpf_tramp_progs *tprogs, void *orig_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff812273f0)
Location: arch/x86/net/bpf_jit_comp.c:1958
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81bcd0a2-ffffffff81bcd113: arch_prepare_bpf_trampoline.cold (STB_LOCAL)
ffffffff8109ef30-ffffffff8109f5b0: arch_prepare_bpf_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int arch_prepare_bpf_trampoline(struct bpf_tramp_image *im, void *image, void *image_end, const struct btf_func_model *m, u32 flags, struct bpf_tramp_progs *tprogs, void *orig_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8125f4f0)
Location: arch/x86/net/bpf_jit_comp.c:2003
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81ca3801-ffffffff81ca386f: arch_prepare_bpf_trampoline.cold (STB_LOCAL)
ffffffff810b00f0-ffffffff810b0908: arch_prepare_bpf_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arch_prepare_bpf_trampoline(struct bpf_tramp_image *im, void *image, void *image_end, const struct btf_func_model *m, u32 flags, struct bpf_tramp_links *tlinks, void *orig_call);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff812a9c50)
Location: arch/x86/net/bpf_jit_comp.c:2022
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff81e52efb-ffffffff81e52f63: arch_prepare_bpf_trampoline.cold (STB_LOCAL)
ffffffff810c5ed0-ffffffff810c67d2: arch_prepare_bpf_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_prepare_bpf_trampoline(struct bpf_tramp_image *im, void *image, void *image_end, const struct btf_func_model *m, u32 flags, struct bpf_tramp_links *tlinks, void *func_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e2cb0)
Location: arch/x86/net/bpf_jit_comp.c:2128
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810e2cb0-ffffffff810e373c: arch_prepare_bpf_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_prepare_bpf_trampoline(struct bpf_tramp_image *im, void *image, void *image_end, const struct btf_func_model *m, u32 flags, struct bpf_tramp_links *tlinks, void *func_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ee380)
Location: arch/x86/net/bpf_jit_comp.c:2133
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
**Symbols:**

```
ffffffff810ee380-ffffffff810eedcb: arch_prepare_bpf_trampoline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_prepare_bpf_trampoline(struct bpf_tramp_image *im, void *image, void *image_end, const struct btf_func_model *m, u32 flags, struct bpf_tramp_links *tlinks, void *func_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f7ee0)
Location: arch/x86/net/bpf_jit_comp.c:2791
Inline: False
Direct callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_prepare_trampoline
```
**Symbols:**

```
ffffffff810f7ee0-ffffffff810f7faa: arch_prepare_bpf_trampoline (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_tramp_image *im</code>
</li>
<li>
<b>Param reordered. </b>
<code>image, image_end, m, flags, tprogs, orig_call</code> ➡️ <code>im, image, image_end, m, flags, tprogs, orig_call</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_tramp_links *tlinks</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_tramp_progs *tprogs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *func_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>void *orig_call</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
