# Function: <code>bpf_core_format_spec</code>

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
int bpf_core_format_spec(char *buf, size_t buf_sz, const struct bpf_core_spec *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff812cae40)
Location: tools/lib/bpf/relo_core.c:1057
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff812cae40-ffffffff812cb1b9: bpf_core_format_spec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_core_format_spec(char *buf, size_t buf_sz, const struct bpf_core_spec *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff813321e0)
Location: tools/lib/bpf/relo_core.c:1156
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff813321e0-ffffffff813325ad: bpf_core_format_spec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_core_format_spec(char *buf, size_t buf_sz, const struct bpf_core_spec *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81362e80)
Location: tools/lib/bpf/relo_core.c:1156
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff81362e80-ffffffff8136325b: bpf_core_format_spec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_core_format_spec(char *buf, size_t buf_sz, const struct bpf_core_spec *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff8138bd50)
Location: tools/lib/bpf/relo_core.c:1156
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff8138bd50-ffffffff8138c12b: bpf_core_format_spec (STB_GLOBAL)
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
