# Function: <code>bpf_core_calc_relo</code>

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
int bpf_core_calc_relo(const char *prog_name, const struct bpf_core_relo *relo, int relo_idx, const struct bpf_core_spec *local_spec, const struct bpf_core_spec *targ_spec, struct bpf_core_relo_res *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff812ca080)
Location: tools/lib/bpf/relo_core.c:783
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff812ca080-ffffffff812ca3d5: bpf_core_calc_relo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_core_calc_relo(const char *prog_name, const struct bpf_core_relo *relo, int relo_idx, const struct bpf_core_spec *local_spec, const struct bpf_core_spec *targ_spec, struct bpf_core_relo_res *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff813311d0)
Location: tools/lib/bpf/relo_core.c:879
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff813311d0-ffffffff8133142c: bpf_core_calc_relo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_core_calc_relo(const char *prog_name, const struct bpf_core_relo *relo, int relo_idx, const struct bpf_core_spec *local_spec, const struct bpf_core_spec *targ_spec, struct bpf_core_relo_res *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81361e70)
Location: tools/lib/bpf/relo_core.c:879
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff81361e70-ffffffff813620d3: bpf_core_calc_relo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_core_calc_relo(const char *prog_name, const struct bpf_core_relo *relo, int relo_idx, const struct bpf_core_spec *local_spec, const struct bpf_core_spec *targ_spec, struct bpf_core_relo_res *res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff8138ad40)
Location: tools/lib/bpf/relo_core.c:879
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff8138ad40-ffffffff8138afa3: bpf_core_calc_relo (STB_LOCAL)
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
