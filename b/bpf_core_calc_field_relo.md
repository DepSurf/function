# Function: <code>bpf_core_calc_field_relo</code>

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
int bpf_core_calc_field_relo(const char *prog_name, const struct bpf_core_relo *relo, const struct bpf_core_spec *spec, __u32 *val, __u32 *field_sz, __u32 *type_id, bool *validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff812c9c70)
Location: tools/lib/bpf/relo_core.c:583
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
```
**Symbols:**

```
ffffffff812c9c70-ffffffff812ca072: bpf_core_calc_field_relo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_core_calc_field_relo(const char *prog_name, const struct bpf_core_relo *relo, const struct bpf_core_spec *spec, __u64 *val, __u32 *field_sz, __u32 *type_id, bool *validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81330da0)
Location: tools/lib/bpf/relo_core.c:678
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
```
**Symbols:**

```
ffffffff81330da0-ffffffff813311bb: bpf_core_calc_field_relo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_core_calc_field_relo(const char *prog_name, const struct bpf_core_relo *relo, const struct bpf_core_spec *spec, __u64 *val, __u32 *field_sz, __u32 *type_id, bool *validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81361a40)
Location: tools/lib/bpf/relo_core.c:678
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
```
**Symbols:**

```
ffffffff81361a40-ffffffff81361e60: bpf_core_calc_field_relo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_core_calc_field_relo(const char *prog_name, const struct bpf_core_relo *relo, const struct bpf_core_spec *spec, __u64 *val, __u32 *field_sz, __u32 *type_id, bool *validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff8138a8f0)
Location: tools/lib/bpf/relo_core.c:678
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
```
**Symbols:**

```
ffffffff8138a8f0-ffffffff8138ad2e: bpf_core_calc_field_relo (STB_LOCAL)
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
<b>Param type changed. </b>
<code>__u32 *val</code> ➡️ <code>__u64 *val</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
