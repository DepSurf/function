# Function: <code>bpf_prog_pack_alloc</code>

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
void *bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126c1b0)
Location: kernel/bpf/core.c:895
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
```
**Symbols:**

```
ffffffff8126c1b0-ffffffff8126c3ae: bpf_prog_pack_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2860)
Location: kernel/bpf/core.c:876
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff812c2860-ffffffff812c29e1: bpf_prog_pack_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9750)
Location: kernel/bpf/core.c:877
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff812e9750-ffffffff812e98d6: bpf_prog_pack_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_prog_pack_alloc(u32 size, bpf_jit_fill_hole_t bpf_fill_ill_insns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81307db0)
Location: kernel/bpf/core.c:920
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_alloc_bpf_trampoline
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff81307db0-ffffffff81307f36: bpf_prog_pack_alloc (STB_GLOBAL)
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
