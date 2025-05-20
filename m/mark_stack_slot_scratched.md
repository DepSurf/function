# Function: <code>mark_stack_slot_scratched</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812853fc)
Location: kernel/bpf/verifier.c:641
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
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
In kernel/bpf/verifier.c (ffffffff812e0d14)
Location: kernel/bpf/verifier.c:701
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
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
In kernel/bpf/verifier.c (ffffffff81314c86)
Location: kernel/bpf/verifier.c:783
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
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
In kernel/bpf/verifier.c (ffffffff813364f5)
Location: include/linux/bpf_verifier.h:887
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_reg_stack_read
  - kernel/bpf/verifier.c:check_stack_write_var_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
  - kernel/bpf/verifier.c:destroy_if_dynptr_stack_slot
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
