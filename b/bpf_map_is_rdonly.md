# Function: <code>bpf_map_is_rdonly</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8121055d)
Location: kernel/bpf/verifier.c:3105
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81211246)
Location: kernel/bpf/verifier.c:3263
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81213f38)
Location: kernel/bpf/verifier.c:3806
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_map_is_rdonly(const struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81248947)
Location: kernel/bpf/verifier.c:3892
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81235e50-ffffffff81235e91: bpf_map_is_rdonly (STB_LOCAL)
ffffffff81cb7c39-ffffffff81cb7c4d: bpf_map_is_rdonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_map_is_rdonly(const struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8128f239)
Location: kernel/bpf/verifier.c:4419
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81279c90-ffffffff81279cef: bpf_map_is_rdonly (STB_LOCAL)
ffffffff81e68dd7-ffffffff81e68dec: bpf_map_is_rdonly.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812eb842)
Location: kernel/bpf/verifier.c:4874
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81317fde)
Location: kernel/bpf/verifier.c:5818
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8132e680)
Location: kernel/bpf/verifier.c:6191
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_reg_const_str
  - kernel/bpf/verifier.c:check_mem_access
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
