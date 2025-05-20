# Function: <code>bpf_prog_map_compatible</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map *map, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e739)
Location: kernel/bpf/core.c:2117
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff8126bc80-ffffffff8126bd70: bpf_prog_map_compatible.part.0 (STB_LOCAL)
ffffffff81e689cd-ffffffff81e68a20: bpf_prog_map_compatible.part.0.cold (STB_LOCAL)
ffffffff8126dea0-ffffffff8126dec9: bpf_prog_map_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map *map, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:2089
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff8205f753-ffffffff8205f7a5: bpf_prog_map_compatible.cold (STB_LOCAL)
ffffffff812c3320-ffffffff812c3440: bpf_prog_map_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map *map, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:2098
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff820de67a-ffffffff820de6e1: bpf_prog_map_compatible.cold (STB_LOCAL)
ffffffff812ea150-ffffffff812ea289: bpf_prog_map_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool bpf_prog_map_compatible(struct bpf_map *map, const struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (0)
Location: kernel/bpf/core.c:2274
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
  - kernel/bpf/arraymap.c:prog_fd_array_get_ptr
  - kernel/bpf/devmap.c:__dev_map_alloc_node
  - kernel/bpf/cpumap.c:__cpu_map_entry_alloc
```
**Symbols:**

```
ffffffff821ba500-ffffffff821ba567: bpf_prog_map_compatible.cold (STB_LOCAL)
ffffffff81308460-ffffffff81308599: bpf_prog_map_compatible (STB_GLOBAL)
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
