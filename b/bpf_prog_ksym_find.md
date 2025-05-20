# Function: <code>bpf_prog_ksym_find</code>

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
In kernel/bpf/core.c (ffffffff811fa32e)
Location: kernel/bpf/core.c:711
Inline: True
Inline callers:
  - kernel/bpf/core.c:search_bpf_extables
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
In kernel/bpf/core.c (ffffffff811f9370)
Location: kernel/bpf/core.c:707
Inline: True
Inline callers:
  - kernel/bpf/core.c:search_bpf_extables
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
In kernel/bpf/core.c (ffffffff811fa200)
Location: kernel/bpf/core.c:713
Inline: True
Inline callers:
  - kernel/bpf/core.c:search_bpf_extables
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122b8d3)
Location: kernel/bpf/core.c:714
Inline: True
Inline callers:
  - kernel/bpf/core.c:search_bpf_extables
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126d3a8)
Location: kernel/bpf/core.c:717
Inline: True
Inline callers:
  - kernel/bpf/core.c:search_bpf_extables
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
In kernel/bpf/core.c (ffffffff812c2548)
Location: kernel/bpf/core.c:725
Inline: True
Inline callers:
  - kernel/bpf/core.c:search_bpf_extables
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
In kernel/bpf/core.c (ffffffff812e9408)
Location: kernel/bpf/core.c:726
Inline: True
Inline callers:
  - kernel/bpf/core.c:search_bpf_extables
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_prog *bpf_prog_ksym_find(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/core.c (ffffffff813077f8)
Location: kernel/bpf/core.c:769
Inline: True
Inline callers:
  - kernel/bpf/core.c:search_bpf_extables
```
**Symbols:**

```
ffffffff821ba45f-ffffffff821ba47b: bpf_prog_ksym_find.cold (STB_LOCAL)
ffffffff81307770-ffffffff813077c2: bpf_prog_ksym_find (STB_GLOBAL)
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
</ul>
