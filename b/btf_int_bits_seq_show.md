# Function: <code>btf_int_bits_seq_show</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:989
Inline: True
Direct callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
**Symbols:**

```
ffffffff811c7ba0-ffffffff811c7c9e: btf_int_bits_seq_show.constprop.23 (STB_LOCAL)
ffffffff811c971e-ffffffff811c972a: btf_int_bits_seq_show.constprop.23.cold.25 (STB_LOCAL)
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
In kernel/bpf/btf.c (ffffffff811da49f)
Location: kernel/bpf/btf.c:1242
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (ffffffff811ef3e4)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (ffffffff811fbb24)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (ffffffff81220503)
Location: kernel/bpf/btf.c:1519
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/bpf/btf.c (ffff800010281fe4)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (c04b1c8c)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (c00000000032c530)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (ffffffe0001b8140)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (ffffffff811f4144)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (ffffffff811e6e94)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (ffffffff811f1f14)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
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
In kernel/bpf/btf.c (ffffffff81200424)
Location: kernel/bpf/btf.c:1413
Inline: True
Inline callers:
  - kernel/bpf/btf.c:btf_int_seq_show
  - kernel/bpf/btf.c:btf_int_seq_show
```
</details>
</li>
</ul>

## Differences
