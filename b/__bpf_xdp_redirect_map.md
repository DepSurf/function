# Function: <code>__bpf_xdp_redirect_map</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81232de9)
Location: include/linux/filter.h:1482
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:dev_map_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff81233405)
Location: include/linux/filter.h:1482
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
```
```
In net/xdp/xskmap.c (ffffffff81ba7945)
Location: include/linux/filter.h:1482
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
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
In kernel/bpf/devmap.c (ffffffff8126c3a5)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:dev_map_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff8126d055)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
```
```
In net/xdp/xskmap.c (ffffffff81c755c5)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
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
In kernel/bpf/devmap.c (ffffffff812bb0c5)
Location: include/linux/filter.h:1531
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:dev_map_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff812bbde5)
Location: include/linux/filter.h:1531
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
```
```
In net/xdp/xskmap.c (ffffffff81e197e5)
Location: include/linux/filter.h:1531
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
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
In kernel/bpf/devmap.c (ffffffff8131e505)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:dev_map_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff8131f1b5)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
```
```
In net/xdp/xskmap.c (ffffffff81ff0b55)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
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
In kernel/bpf/devmap.c (ffffffff8134e309)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:dev_map_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff8134f005)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
```
```
In net/xdp/xskmap.c (ffffffff8206ccc5)
Location: include/linux/filter.h:1506
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
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
In kernel/bpf/devmap.c (ffffffff81375809)
Location: include/linux/filter.h:1543
Inline: True
Inline callers:
  - kernel/bpf/devmap.c:dev_hash_map_redirect
  - kernel/bpf/devmap.c:dev_map_redirect
```
```
In kernel/bpf/cpumap.c (ffffffff81376505)
Location: include/linux/filter.h:1543
Inline: True
Inline callers:
  - kernel/bpf/cpumap.c:cpu_map_redirect
```
```
In net/xdp/xskmap.c (ffffffff82140b65)
Location: include/linux/filter.h:1543
Inline: True
Inline callers:
  - net/xdp/xskmap.c:xsk_map_redirect
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
