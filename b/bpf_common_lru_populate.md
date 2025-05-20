# Function: <code>bpf_common_lru_populate</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bpf_common_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196d6e)
Location: kernel/bpf/bpf_lru_list.c:561
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
**Symbols:**

```
ffffffff81196c20-ffffffff81196c63: bpf_common_lru_populate (STB_GLOBAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff8119e04e)
Location: kernel/bpf/bpf_lru_list.c:561
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (ffffffff811adc5e)
Location: kernel/bpf/bpf_lru_list.c:561
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:561
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:561
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:559
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:559
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:559
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:559
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:559
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:564
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:564
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (ffffffe0001b45d0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:558
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
