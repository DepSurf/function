# Function: <code>bpf_bypass_spec_v1</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8121312b)
Location: include/linux/bpf.h:1112
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/arraymap.c (ffffffff8121a64b)
Location: include/linux/bpf.h:1112
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81214924)
Location: include/linux/bpf.h:1294
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/arraymap.c (ffffffff8121d35a)
Location: include/linux/bpf.h:1294
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8121719a)
Location: include/linux/bpf.h:1354
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/arraymap.c (ffffffff81220e6a)
Location: include/linux/bpf.h:1354
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8124d9bc)
Location: include/linux/bpf.h:1437
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/arraymap.c (ffffffff8125882a)
Location: include/linux/bpf.h:1437
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8129495e)
Location: include/linux/bpf.h:1558
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/arraymap.c (ffffffff812a163a)
Location: include/linux/bpf.h:1558
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ef512)
Location: include/linux/bpf.h:1919
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/arraymap.c (ffffffff812fe89a)
Location: include/linux/bpf.h:1919
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131be65)
Location: include/linux/bpf.h:2055
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/arraymap.c (ffffffff8132d48a)
Location: include/linux/bpf.h:2055
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8133e204)
Location: include/linux/bpf.h:2215
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In kernel/bpf/arraymap.c (ffffffff8135182a)
Location: include/linux/bpf.h:2215
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:array_map_alloc
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
