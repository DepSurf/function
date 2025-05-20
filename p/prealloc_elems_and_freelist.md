# Function: <code>prealloc_elems_and_freelist</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81186569)
Location: kernel/bpf/hashtab.c:90
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
```
In kernel/bpf/stackmap.c (ffffffff8118830c)
Location: kernel/bpf/stackmap.c:30
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811971de)
Location: kernel/bpf/stackmap.c:29
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8119ee39)
Location: kernel/bpf/stackmap.c:29
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811b1dc7)
Location: kernel/bpf/stackmap.c:32
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811d0b7c)
Location: kernel/bpf/stackmap.c:64
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811e065c)
Location: kernel/bpf/stackmap.c:64
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811f6210)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812031d0)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8122b029)
Location: kernel/bpf/stackmap.c:63
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
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
In kernel/bpf/stackmap.c (ffffffff81232f52)
Location: kernel/bpf/stackmap.c:65
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
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
In kernel/bpf/stackmap.c (ffffffff812370f2)
Location: kernel/bpf/stackmap.c:64
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
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
In kernel/bpf/stackmap.c (ffffffff812716df)
Location: kernel/bpf/stackmap.c:64
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
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
In kernel/bpf/stackmap.c (ffffffff812c083d)
Location: kernel/bpf/stackmap.c:45
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
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
In kernel/bpf/stackmap.c (ffffffff813240cd)
Location: kernel/bpf/stackmap.c:45
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
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
In kernel/bpf/stackmap.c (ffffffff8135433f)
Location: kernel/bpf/stackmap.c:45
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
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
In kernel/bpf/stackmap.c (ffffffff8137ccaf)
Location: kernel/bpf/stackmap.c:45
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffff80001028b8c8)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (c04bafb4)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (c00000000033787c)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffe0001bf4e8)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811fb7f0)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811ee540)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811f95c0)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81208060)
Location: kernel/bpf/stackmap.c:61
Inline: True
Inline callers:
  - kernel/bpf/stackmap.c:stack_map_alloc
```
</details>
</li>
</ul>

## Differences
