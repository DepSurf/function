# Function: <code>bpf_core_parse_spec</code>

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
int bpf_core_parse_spec(const char *prog_name, const struct btf *btf, const struct bpf_core_relo *relo, struct bpf_core_spec *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff812ca3e0)
Location: tools/lib/bpf/relo_core.c:181
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff812ca3e0-ffffffff812ca9b5: bpf_core_parse_spec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_core_parse_spec(const char *prog_name, const struct btf *btf, const struct bpf_core_relo *relo, struct bpf_core_spec *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81331740)
Location: tools/lib/bpf/relo_core.c:263
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff81331740-ffffffff81331d3d: bpf_core_parse_spec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_core_parse_spec(const char *prog_name, const struct btf *btf, const struct bpf_core_relo *relo, struct bpf_core_spec *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff813623d0)
Location: tools/lib/bpf/relo_core.c:263
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff813623d0-ffffffff813629df: bpf_core_parse_spec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_core_parse_spec(const char *prog_name, const struct btf *btf, const struct bpf_core_relo *relo, struct bpf_core_spec *spec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff8138b2a0)
Location: tools/lib/bpf/relo_core.c:263
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo_insn
```
**Symbols:**

```
ffffffff8138b2a0-ffffffff8138b8af: bpf_core_parse_spec (STB_GLOBAL)
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
