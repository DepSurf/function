# Function: <code>dynptr_get_spi</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dynptr_get_spi(struct bpf_verifier_env *env, struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d7d30)
Location: kernel/bpf/verifier.c:646
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff812d7d30-ffffffff812d7d9a: dynptr_get_spi (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff813160d1)
Location: kernel/bpf/verifier.c:720
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
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
In kernel/bpf/verifier.c (ffffffff813371ed)
Location: kernel/bpf/verifier.c:615
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
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
<b>Regular</b>
<ul>
</ul>
