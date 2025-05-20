# Function: <code>bpf_jit_binary_pack_free</code>

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
void bpf_jit_binary_pack_free(struct bpf_binary_header *ro_header, struct bpf_binary_header *rw_header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126ec80)
Location: kernel/bpf/core.c:1162
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8126ec80-ffffffff8126ecb3: bpf_jit_binary_pack_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_jit_binary_pack_free(struct bpf_binary_header *ro_header, struct bpf_binary_header *rw_header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c4480)
Location: kernel/bpf/core.c:1136
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff812c4480-ffffffff812c44b3: bpf_jit_binary_pack_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_jit_binary_pack_free(struct bpf_binary_header *ro_header, struct bpf_binary_header *rw_header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812eb430)
Location: kernel/bpf/core.c:1137
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff812eb430-ffffffff812eb463: bpf_jit_binary_pack_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_jit_binary_pack_free(struct bpf_binary_header *ro_header, struct bpf_binary_header *rw_header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81309930)
Location: kernel/bpf/core.c:1179
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81309930-ffffffff81309965: bpf_jit_binary_pack_free (STB_GLOBAL)
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
