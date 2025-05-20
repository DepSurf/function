# Function: <code>btf_find_dtor_kfunc</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
s32 btf_find_dtor_kfunc(struct btf *btf, u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7c66)
Location: kernel/bpf/btf.c:7177
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_kptrs
```
**Symbols:**

```
ffffffff812b8e50-ffffffff812b8eb3: btf_find_dtor_kfunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
s32 btf_find_dtor_kfunc(struct btf *btf, u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81319957)
Location: kernel/bpf/btf.c:7670
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_fields
```
**Symbols:**

```
ffffffff8131adf0-ffffffff8131ae53: btf_find_dtor_kfunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
s32 btf_find_dtor_kfunc(struct btf *btf, u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81349023)
Location: kernel/bpf/btf.c:7931
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_kptr
```
**Symbols:**

```
ffffffff8134a3e0-ffffffff8134a443: btf_find_dtor_kfunc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
s32 btf_find_dtor_kfunc(struct btf *btf, u32 btf_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8136f753)
Location: kernel/bpf/btf.c:7996
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_parse_kptr
```
**Symbols:**

```
ffffffff81370b90-ffffffff81370bf3: btf_find_dtor_kfunc (STB_GLOBAL)
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
