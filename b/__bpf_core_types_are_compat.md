# Function: <code>__bpf_core_types_are_compat</code>

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
int __bpf_core_types_are_compat(const struct btf *local_btf, __u32 local_id, const struct btf *targ_btf, __u32 targ_id, int level);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff812b2350)
Location: kernel/bpf/btf.c:7312
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_types_are_compat
  - kernel/bpf/btf.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff812b2350-ffffffff812b25e8: __bpf_core_types_are_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __bpf_core_types_are_compat(const struct btf *local_btf, __u32 local_id, const struct btf *targ_btf, __u32 targ_id, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff81331440)
Location: tools/lib/bpf/relo_core.c:146
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff81331440-ffffffff81331726: __bpf_core_types_are_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __bpf_core_types_are_compat(const struct btf *local_btf, __u32 local_id, const struct btf *targ_btf, __u32 targ_id, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff813620f0)
Location: tools/lib/bpf/relo_core.c:146
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff813620f0-ffffffff813623c0: __bpf_core_types_are_compat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __bpf_core_types_are_compat(const struct btf *local_btf, __u32 local_id, const struct btf *targ_btf, __u32 targ_id, int level);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In tools/lib/bpf/relo_core.c (ffffffff8138afc0)
Location: tools/lib/bpf/relo_core.c:146
Inline: False
Direct callers:
  - kernel/bpf/btf.c:bpf_core_types_are_compat
  - tools/lib/bpf/relo_core.c:__bpf_core_types_are_compat
```
**Symbols:**

```
ffffffff8138afc0-ffffffff8138b290: __bpf_core_types_are_compat (STB_GLOBAL)
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
