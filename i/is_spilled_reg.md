# Function: <code>is_spilled_reg</code>

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
In kernel/bpf/verifier.c (ffffffff8128d4cd)
Location: kernel/bpf/verifier.c:803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:states_equal
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:print_verifier_state
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
In kernel/bpf/verifier.c (ffffffff812e63b8)
Location: kernel/bpf/verifier.c:992
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:propagate_precision
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:__mark_chain_precision
  - kernel/bpf/verifier.c:print_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8130db7c)
Location: kernel/bpf/verifier.c:1325
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:propagate_precision
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:mark_all_scalars_precise
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
In kernel/bpf/verifier.c (ffffffff8132a449)
Location: kernel/bpf/verifier.c:1147
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:propagate_precision
  - kernel/bpf/verifier.c:widen_imprecise_scalars
  - kernel/bpf/verifier.c:widen_imprecise_scalars
  - kernel/bpf/verifier.c:check_stack_range_initialized
  - kernel/bpf/verifier.c:check_stack_read_fixed_off
  - kernel/bpf/verifier.c:check_stack_write_fixed_off
  - kernel/bpf/verifier.c:mark_all_scalars_precise
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
