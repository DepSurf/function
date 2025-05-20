# Function: <code>bpf_jit_binary_pack_hdr</code>

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
struct bpf_binary_header *bpf_jit_binary_pack_hdr(const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d850)
Location: kernel/bpf/core.c:1173
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
**Symbols:**

```
ffffffff8126d850-ffffffff8126d869: bpf_jit_binary_pack_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_binary_header *bpf_jit_binary_pack_hdr(const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2c60)
Location: kernel/bpf/core.c:1147
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
**Symbols:**

```
ffffffff812c2c60-ffffffff812c2c79: bpf_jit_binary_pack_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_binary_header *bpf_jit_binary_pack_hdr(const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9b50)
Location: kernel/bpf/core.c:1148
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
**Symbols:**

```
ffffffff812e9b50-ffffffff812e9b69: bpf_jit_binary_pack_hdr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_binary_header *bpf_jit_binary_pack_hdr(const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff813080a0)
Location: kernel/bpf/core.c:1190
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
**Symbols:**

```
ffffffff813080a0-ffffffff813080b9: bpf_jit_binary_pack_hdr (STB_GLOBAL)
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
