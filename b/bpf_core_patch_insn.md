# Function: <code>bpf_core_patch_insn</code>

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
int bpf_core_patch_insn(const char *prog_name, struct bpf_insn *insn, int insn_idx, const struct bpf_core_relo *relo, int relo_idx, const struct bpf_core_relo_res *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In tools/lib/bpf/relo_core.c (0)
Location: tools/lib/bpf/relo_core.c:928
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
**Symbols:**

```
ffffffff81e6acf6-ffffffff81e6adce: bpf_core_patch_insn.cold (STB_LOCAL)
ffffffff812ca9c0-ffffffff812cae32: bpf_core_patch_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_core_patch_insn(const char *prog_name, struct bpf_insn *insn, int insn_idx, const struct bpf_core_relo *relo, int relo_idx, const struct bpf_core_relo_res *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In tools/lib/bpf/relo_core.c (0)
Location: tools/lib/bpf/relo_core.c:1024
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
**Symbols:**

```
ffffffff82061c64-ffffffff82061d3c: bpf_core_patch_insn.cold (STB_LOCAL)
ffffffff81331d50-ffffffff813321c4: bpf_core_patch_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_core_patch_insn(const char *prog_name, struct bpf_insn *insn, int insn_idx, const struct bpf_core_relo *relo, int relo_idx, const struct bpf_core_relo_res *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In tools/lib/bpf/relo_core.c (0)
Location: tools/lib/bpf/relo_core.c:1024
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
**Symbols:**

```
ffffffff820e13e0-ffffffff820e14b8: bpf_core_patch_insn.cold (STB_LOCAL)
ffffffff813629f0-ffffffff81362e61: bpf_core_patch_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_core_patch_insn(const char *prog_name, struct bpf_insn *insn, int insn_idx, const struct bpf_core_relo *relo, int relo_idx, const struct bpf_core_relo_res *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In tools/lib/bpf/relo_core.c (0)
Location: tools/lib/bpf/relo_core.c:1024
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
**Symbols:**

```
ffffffff821bddef-ffffffff821bdec7: bpf_core_patch_insn.cold (STB_LOCAL)
ffffffff8138b8c0-ffffffff8138bd31: bpf_core_patch_insn (STB_GLOBAL)
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
