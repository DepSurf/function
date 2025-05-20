# Function: <code>bpf_core_calc_type_relo</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff812ca23e)
Location: tools/lib/bpf/relo_core.c:709
Inline: True
Inline callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_core_calc_type_relo(const struct bpf_core_relo *relo, const struct bpf_core_spec *spec, __u64 *val, bool *validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81330880)
Location: tools/lib/bpf/relo_core.c:803
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
```
**Symbols:**

```
ffffffff81330880-ffffffff81330977: bpf_core_calc_type_relo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_core_calc_type_relo(const struct bpf_core_relo *relo, const struct bpf_core_spec *spec, __u64 *val, bool *validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81361550)
Location: tools/lib/bpf/relo_core.c:803
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
```
**Symbols:**

```
ffffffff81361550-ffffffff81361639: bpf_core_calc_type_relo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_core_calc_type_relo(const struct bpf_core_relo *relo, const struct bpf_core_spec *spec, __u64 *val, bool *validate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff8138a400)
Location: tools/lib/bpf/relo_core.c:803
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
  - tools/lib/bpf/relo_core.c:bpf_core_calc_relo
```
**Symbols:**

```
ffffffff8138a400-ffffffff8138a4e9: bpf_core_calc_type_relo (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
