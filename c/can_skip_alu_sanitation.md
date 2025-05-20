# Function: <code>can_skip_alu_sanitation</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7945)
Location: kernel/bpf/verifier.c:3109
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (ffffffff811db035)
Location: kernel/bpf/verifier.c:4232
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (ffffffff811e7785)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (ffffffff81203205)
Location: kernel/bpf/verifier.c:4912
Inline: True
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
In kernel/bpf/verifier.c (ffffffff812030a5)
Location: kernel/bpf/verifier.c:5423
Inline: True
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
In kernel/bpf/verifier.c (ffffffff81209ace)
Location: kernel/bpf/verifier.c:6424
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff8123d806)
Location: kernel/bpf/verifier.c:6713
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_ptr_alu
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
In kernel/bpf/verifier.c (ffffffff8128322a)
Location: kernel/bpf/verifier.c:7712
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_ptr_alu
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
In kernel/bpf/verifier.c (ffffffff812dad6a)
Location: kernel/bpf/verifier.c:9648
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_ptr_alu
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
In kernel/bpf/verifier.c (ffffffff813104b8)
Location: kernel/bpf/verifier.c:11564
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_ptr_alu
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
In kernel/bpf/verifier.c (ffffffff81331048)
Location: kernel/bpf/verifier.c:12498
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:sanitize_ptr_alu
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
In kernel/bpf/verifier.c (ffff8000102662bc)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (c049d26c)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (c00000000030afb8)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (ffffffe0001a1732)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (ffffffff811dfda5)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (ffffffff811d2b65)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (ffffffff811ddb75)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_val_alu
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
In kernel/bpf/verifier.c (ffffffff811ebf85)
Location: kernel/bpf/verifier.c:4235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:sanitize_ptr_alu
  - kernel/bpf/verifier.c:sanitize_val_alu
```
</details>
</li>
</ul>

## Differences
