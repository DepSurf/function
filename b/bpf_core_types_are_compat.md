# Function: <code>bpf_core_types_are_compat</code>

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
int bpf_core_types_are_compat(const struct btf *local_btf, __u32 local_id, const struct btf *targ_btf, __u32 targ_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b8ec0)
Location: kernel/bpf/btf.c:7410
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
```
**Symbols:**

```
ffffffff812b8ec0-ffffffff812b8ee5: bpf_core_types_are_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_core_types_are_compat(const struct btf *local_btf, __u32 local_id, const struct btf *targ_btf, __u32 targ_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8131ae70)
Location: kernel/bpf/btf.c:7823
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
```
**Symbols:**

```
ffffffff8131ae70-ffffffff8131ae95: bpf_core_types_are_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_core_types_are_compat(const struct btf *local_btf, __u32 local_id, const struct btf *targ_btf, __u32 targ_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8134a460)
Location: kernel/bpf/btf.c:8084
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
```
**Symbols:**

```
ffffffff8134a460-ffffffff8134a485: bpf_core_types_are_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_core_types_are_compat(const struct btf *local_btf, __u32 local_id, const struct btf *targ_btf, __u32 targ_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81370c10)
Location: kernel/bpf/btf.c:8149
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_spec_match
```
**Symbols:**

```
ffffffff81370c10-ffffffff81370c35: bpf_core_types_are_compat (STB_GLOBAL)
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
