# Function: <code>bpf_core_names_match</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_core_names_match(const struct btf *local_btf, size_t local_name_off, const struct btf *targ_btf, size_t targ_name_off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81330290)
Location: tools/lib/bpf/relo_core.c:1422
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
```
**Symbols:**

```
ffffffff81330290-ffffffff8133033b: bpf_core_names_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_core_names_match(const struct btf *local_btf, size_t local_name_off, const struct btf *targ_btf, size_t targ_name_off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81360f30)
Location: tools/lib/bpf/relo_core.c:1422
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
```
**Symbols:**

```
ffffffff81360f30-ffffffff81360fdb: bpf_core_names_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_core_names_match(const struct btf *local_btf, size_t local_name_off, const struct btf *targ_btf, size_t targ_name_off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81389de0)
Location: tools/lib/bpf/relo_core.c:1422
Inline: False
Direct callers:
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
  - tools/lib/bpf/relo_core.c:__bpf_core_types_match
```
**Symbols:**

```
ffffffff81389de0-ffffffff81389e8b: bpf_core_names_match (STB_LOCAL)
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
