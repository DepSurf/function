# Function: <code>bpf_jit_binary_pack_alloc</code>

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
struct bpf_binary_header *bpf_jit_binary_pack_alloc(unsigned int proglen, u8 **image_ptr, unsigned int alignment, struct bpf_binary_header **rw_header, u8 **rw_image, bpf_jit_fill_hole_t bpf_fill_ill_insns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126eab0)
Location: kernel/bpf/core.c:1089
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8126eab0-ffffffff8126ec09: bpf_jit_binary_pack_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_binary_header *bpf_jit_binary_pack_alloc(unsigned int proglen, u8 **image_ptr, unsigned int alignment, struct bpf_binary_header **rw_header, u8 **rw_image, bpf_jit_fill_hole_t bpf_fill_ill_insns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c4290)
Location: kernel/bpf/core.c:1063
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff812c4290-ffffffff812c43e3: bpf_jit_binary_pack_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_binary_header *bpf_jit_binary_pack_alloc(unsigned int proglen, u8 **image_ptr, unsigned int alignment, struct bpf_binary_header **rw_header, u8 **rw_image, bpf_jit_fill_hole_t bpf_fill_ill_insns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812eb240)
Location: kernel/bpf/core.c:1064
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff812eb240-ffffffff812eb393: bpf_jit_binary_pack_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_binary_header *bpf_jit_binary_pack_alloc(unsigned int proglen, u8 **image_ptr, unsigned int alignment, struct bpf_binary_header **rw_header, u8 **rw_image, bpf_jit_fill_hole_t bpf_fill_ill_insns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81309770)
Location: kernel/bpf/core.c:1107
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81309770-ffffffff81309891: bpf_jit_binary_pack_alloc (STB_GLOBAL)
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
