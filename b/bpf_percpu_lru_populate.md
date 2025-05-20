# Function: <code>bpf_percpu_lru_populate</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_percpu_lru_populate(struct bpf_lru *lru, void *buf, u32 node_offset, u32 elem_size, u32 nr_elems);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196c70)
Location: kernel/bpf/bpf_lru_list.c:578
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_populate
```
**Symbols:**

```
ffffffff81196c70-ffffffff81196d53: bpf_percpu_lru_populate (STB_GLOBAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff8119e094)
Location: kernel/bpf/bpf_lru_list.c:579
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
In kernel/bpf/bpf_lru_list.c (ffffffff811adca4)
Location: kernel/bpf/bpf_lru_list.c:579
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
In kernel/bpf/bpf_lru_list.c (ffffffff811c5217)
Location: kernel/bpf/bpf_lru_list.c:579
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
In kernel/bpf/bpf_lru_list.c (ffffffff811d6e17)
Location: kernel/bpf/bpf_lru_list.c:579
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
In kernel/bpf/bpf_lru_list.c (ffffffff811eb807)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f7f67)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (ffffffff8121bce7)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (ffffffff8121ec67)
Location: kernel/bpf/bpf_lru_list.c:577
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
In kernel/bpf/bpf_lru_list.c (ffffffff812226e3)
Location: kernel/bpf/bpf_lru_list.c:577
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
In kernel/bpf/bpf_lru_list.c (ffffffff8125a3d7)
Location: kernel/bpf/bpf_lru_list.c:577
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
In kernel/bpf/bpf_lru_list.c (ffffffff812a3494)
Location: kernel/bpf/bpf_lru_list.c:577
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
In kernel/bpf/bpf_lru_list.c (ffffffff81301008)
Location: kernel/bpf/bpf_lru_list.c:577
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
In kernel/bpf/bpf_lru_list.c (ffffffff8132fb52)
Location: kernel/bpf/bpf_lru_list.c:582
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
In kernel/bpf/bpf_lru_list.c (ffffffff81354072)
Location: kernel/bpf/bpf_lru_list.c:582
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
In kernel/bpf/bpf_lru_list.c (ffff80001027d148)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (c04aeb18)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (c000000000326bd0)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4628)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f0587)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (ffffffff811e32d7)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ee357)
Location: kernel/bpf/bpf_lru_list.c:576
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
In kernel/bpf/bpf_lru_list.c (ffffffff811fc827)
Location: kernel/bpf/bpf_lru_list.c:576
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
