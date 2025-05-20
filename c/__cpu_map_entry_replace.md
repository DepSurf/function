# Function: <code>__cpu_map_entry_replace</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __cpu_map_entry_replace(struct bpf_cpu_map *cmap, u32 key_cpu, struct bpf_cpu_map_entry *rcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811b00b0)
Location: kernel/bpf/cpumap.c:441
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff811b00b0-ffffffff811b0119: __cpu_map_entry_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ca3a0)
Location: kernel/bpf/cpumap.c:404
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff811ca3a0-ffffffff811ca402: __cpu_map_entry_replace.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811ddcc0)
Location: kernel/bpf/cpumap.c:404
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff811ddcc0-ffffffff811ddd22: __cpu_map_entry_replace.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f3390)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff811f3390-ffffffff811f33f2: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81200130)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff81200130-ffffffff81200192: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81228743)
Location: kernel/bpf/cpumap.c:410
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff81227e00-ffffffff81227e65: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8122f613)
Location: kernel/bpf/cpumap.c:509
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff8122eb60-ffffffff8122ebc5: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81234443)
Location: kernel/bpf/cpumap.c:467
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff81233950-ffffffff812339b5: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8126db23)
Location: kernel/bpf/cpumap.c:528
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff8126d610-ffffffff8126d675: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812bd3ec)
Location: kernel/bpf/cpumap.c:531
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff812bc790-ffffffff812bc801: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8132086c)
Location: kernel/bpf/cpumap.c:530
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff8131fb90-ffffffff8131fc01: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8135071c)
Location: kernel/bpf/cpumap.c:541
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
```
**Symbols:**

```
ffffffff8134fbb0-ffffffff8134fc21: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
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
In kernel/bpf/cpumap.c (ffffffff81377183)
Location: kernel/bpf/cpumap.c:498
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffff800010287a60)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffff800010287a60-ffff800010287b00: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __cpu_map_entry_replace(struct bpf_cpu_map *cmap, u32 key_cpu, struct bpf_cpu_map_entry *rcpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (c04b7bc0)
Location: kernel/bpf/cpumap.c:442
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
c04b7bc0-c04b7c4c: __cpu_map_entry_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (c000000000332dc0)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
c000000000332dc0-c000000000332e88: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffe0001bc56e)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffe0001bc56e-ffffffe0001bc5ec: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f8750)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff811f8750-ffffffff811f87b2: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811eb4a0)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff811eb4a0-ffffffff811eb502: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff811f6520)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff811f6520-ffffffff811f6582: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81204aa0)
Location: kernel/bpf/cpumap.c:442
Inline: True
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_free
  - kernel/bpf/cpumap.c:cpu_map_update_elem
  - kernel/bpf/cpumap.c:cpu_map_delete_elem
```
**Symbols:**

```
ffffffff81204aa0-ffffffff81204b02: __cpu_map_entry_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
