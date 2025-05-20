# Function: <code>reg_type_may_be_null</code>

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
In kernel/bpf/verifier.c (ffffffff811cba80)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
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
In kernel/bpf/verifier.c (ffffffff811de5a7)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811ead67)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff8120d268)
Location: kernel/bpf/verifier.c:405
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:__mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:__mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool reg_type_may_be_null(enum bpf_reg_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201780)
Location: kernel/bpf/verifier.c:409
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:__mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:__mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81201780-ffffffff8120179f: reg_type_may_be_null (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8120d4d3)
Location: kernel/bpf/verifier.c:447
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff8124162c)
Location: kernel/bpf/verifier.c:448
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:adjust_ptr_min_max_vals
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
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
In kernel/bpf/verifier.c (ffff80001026e3ac)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (c04a0c68)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (c00000000031510c)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffe0001a84ae)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e3387)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811d6147)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e1157)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811ef567)
Location: kernel/bpf/verifier.c:333
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
