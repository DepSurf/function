# Function: <code>bpf_prog_pack_free</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_prog_pack_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:939
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_finalize
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
```
**Symbols:**

```
ffffffff8126e8f0-ffffffff8126eaa8: bpf_prog_pack_free (STB_LOCAL)
ffffffff81e68acd-ffffffff81e68af6: bpf_prog_pack_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_prog_pack_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:916
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_finalize
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff8205f7b9-ffffffff8205f7e2: bpf_prog_pack_free.cold (STB_LOCAL)
ffffffff812c4080-ffffffff812c427c: bpf_prog_pack_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_prog_pack_free(struct bpf_binary_header *hdr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:917
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_finalize
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff820de6f5-ffffffff820de71e: bpf_prog_pack_free.cold (STB_LOCAL)
ffffffff812eb030-ffffffff812eb22c: bpf_prog_pack_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_prog_pack_free(void *ptr, u32 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:960
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:arch_free_bpf_trampoline
  - kernel/bpf/core.c:bpf_jit_binary_pack_free
  - kernel/bpf/core.c:bpf_jit_binary_pack_finalize
  - kernel/bpf/core.c:bpf_jit_binary_pack_alloc
  - kernel/bpf/dispatcher.c:bpf_dispatcher_change_prog
```
**Symbols:**

```
ffffffff821ba5aa-ffffffff821ba5d3: bpf_prog_pack_free.cold (STB_LOCAL)
ffffffff81309550-ffffffff81309751: bpf_prog_pack_free (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *ptr</code>
</li>
<li>
<b>Param added. </b>
<code>u32 size</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_binary_header *hdr</code>
</li>
</ul>
</details>
</li>
</ul>
