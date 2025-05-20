# Function: <code>realloc_func_state</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int realloc_func_state(struct bpf_func_state *state, int size, bool copy_old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b7550)
Location: kernel/bpf/verifier.c:387
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811b7550-ffffffff811b7691: realloc_func_state (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811c9c54)
Location: kernel/bpf/verifier.c:583
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811e1449)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811edc49)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8120f73a)
Location: kernel/bpf/verifier.c:733
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff812106ca)
Location: kernel/bpf/verifier.c:759
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8120c0e7)
Location: kernel/bpf/verifier.c:808
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
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
In kernel/bpf/verifier.c (ffff800010270dfc)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (c04a30a4)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (c00000000031804c)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffe0001aa306)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:check_stack_write
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811e6269)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811d9029)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811e4039)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff811f2409)
Location: kernel/bpf/verifier.c:606
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:copy_verifier_state
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
