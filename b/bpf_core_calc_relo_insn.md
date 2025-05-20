# Function: <code>bpf_core_calc_relo_insn</code>

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
int bpf_core_calc_relo_insn(const char *prog_name, const struct bpf_core_relo *relo, int relo_idx, const struct btf *local_btf, struct bpf_core_cand_list *cands, struct bpf_core_spec *specs_scratch, struct bpf_core_relo_res *targ_res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In tools/lib/bpf/relo_core.c (0)
Location: tools/lib/bpf/relo_core.c:1169
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
**Symbols:**

```
ffffffff81e6adce-ffffffff81e6ae53: bpf_core_calc_relo_insn.cold (STB_LOCAL)
ffffffff812cb1c0-ffffffff812cb7d0: bpf_core_calc_relo_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int bpf_core_calc_relo_insn(const char *prog_name, const struct bpf_core_relo *relo, int relo_idx, const struct btf *local_btf, struct bpf_core_cand_list *cands, struct bpf_core_spec *specs_scratch, struct bpf_core_relo_res *targ_res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In tools/lib/bpf/relo_core.c (0)
Location: tools/lib/bpf/relo_core.c:1280
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
**Symbols:**

```
ffffffff82061d3c-ffffffff82061dc5: bpf_core_calc_relo_insn.cold (STB_LOCAL)
ffffffff813325c0-ffffffff81332bf3: bpf_core_calc_relo_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int bpf_core_calc_relo_insn(const char *prog_name, const struct bpf_core_relo *relo, int relo_idx, const struct btf *local_btf, struct bpf_core_cand_list *cands, struct bpf_core_spec *specs_scratch, struct bpf_core_relo_res *targ_res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In tools/lib/bpf/relo_core.c (0)
Location: tools/lib/bpf/relo_core.c:1280
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
**Symbols:**

```
ffffffff820e14b8-ffffffff820e1541: bpf_core_calc_relo_insn.cold (STB_LOCAL)
ffffffff81363270-ffffffff813638a3: bpf_core_calc_relo_insn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bpf_core_calc_relo_insn(const char *prog_name, const struct bpf_core_relo *relo, int relo_idx, const struct btf *local_btf, struct bpf_core_cand_list *cands, struct bpf_core_spec *specs_scratch, struct bpf_core_relo_res *targ_res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In tools/lib/bpf/relo_core.c (0)
Location: tools/lib/bpf/relo_core.c:1280
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:bpf_core_apply
```
**Symbols:**

```
ffffffff821bdec7-ffffffff821bdf50: bpf_core_calc_relo_insn.cold (STB_LOCAL)
ffffffff8138c140-ffffffff8138c773: bpf_core_calc_relo_insn (STB_GLOBAL)
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
