# Function: <code>bpf_jit_find_kfunc_model</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct btf_func_model *bpf_jit_find_kfunc_model(const struct bpf_prog *prog, const struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81212a40)
Location: kernel/bpf/verifier.c:1712
Inline: False
```
**Symbols:**

```
ffffffff81212a40-ffffffff81212ab5: bpf_jit_find_kfunc_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct btf_func_model *bpf_jit_find_kfunc_model(const struct bpf_prog *prog, const struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81248340)
Location: kernel/bpf/verifier.c:1780
Inline: False
```
**Symbols:**

```
ffffffff81248340-ffffffff812483b5: bpf_jit_find_kfunc_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct btf_func_model *bpf_jit_find_kfunc_model(const struct bpf_prog *prog, const struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812900d0)
Location: kernel/bpf/verifier.c:2129
Inline: False
```
**Symbols:**

```
ffffffff812900d0-ffffffff8129015c: bpf_jit_find_kfunc_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct btf_func_model *bpf_jit_find_kfunc_model(const struct bpf_prog *prog, const struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812e9040)
Location: kernel/bpf/verifier.c:2344
Inline: False
```
**Symbols:**

```
ffffffff812e9040-ffffffff812e90d5: bpf_jit_find_kfunc_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct btf_func_model *bpf_jit_find_kfunc_model(const struct bpf_prog *prog, const struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813152b0)
Location: kernel/bpf/verifier.c:2774
Inline: False
```
**Symbols:**

```
ffffffff813152b0-ffffffff81315334: bpf_jit_find_kfunc_model (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct btf_func_model *bpf_jit_find_kfunc_model(const struct bpf_prog *prog, const struct bpf_insn *insn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8133cfc0)
Location: kernel/bpf/verifier.c:2847
Inline: False
```
**Symbols:**

```
ffffffff8133cfc0-ffffffff8133d044: bpf_jit_find_kfunc_model (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
