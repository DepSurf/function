# Function: <code>btf_kfunc_id_set_contains</code>

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
bool btf_kfunc_id_set_contains(const struct btf *btf, enum bpf_prog_type prog_type, enum btf_kfunc_type type, u32 kfunc_btf_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b7fb0)
Location: kernel/bpf/btf.c:7137
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/btf.c:btf_check_func_arg_match
  - kernel/bpf/btf.c:btf_check_func_arg_match
```
**Symbols:**

```
ffffffff812b7fb0-ffffffff812b807d: btf_kfunc_id_set_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 *btf_kfunc_id_set_contains(const struct btf *btf, enum bpf_prog_type prog_type, u32 kfunc_btf_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131ac60)
Location: kernel/bpf/btf.c:7606
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_call
```
**Symbols:**

```
ffffffff8131ac60-ffffffff8131ad44: btf_kfunc_id_set_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 *btf_kfunc_id_set_contains(const struct btf *btf, u32 kfunc_btf_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8134a300)
Location: kernel/bpf/btf.c:7858
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fetch_kfunc_meta
```
**Symbols:**

```
ffffffff8134a300-ffffffff8134a38f: btf_kfunc_id_set_contains (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 *btf_kfunc_id_set_contains(const struct btf *btf, u32 kfunc_btf_id, const struct bpf_prog *prog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81370ab0)
Location: kernel/bpf/btf.c:7923
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:fetch_kfunc_meta
```
**Symbols:**

```
ffffffff81370ab0-ffffffff81370b3f: btf_kfunc_id_set_contains (STB_GLOBAL)
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
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum btf_kfunc_type type</code>
</li>
<li>
<b>Param reordered. </b>
<code>btf, prog_type, type, kfunc_btf_id</code> ➡️ <code>btf, prog_type, kfunc_btf_id</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>u32 *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_prog *prog</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_prog_type prog_type</code>
</li>
<li>
<b>Param reordered. </b>
<code>btf, prog_type, kfunc_btf_id</code> ➡️ <code>btf, kfunc_btf_id, prog</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
