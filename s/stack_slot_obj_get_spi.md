# Function: <code>stack_slot_obj_get_spi</code>

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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int stack_slot_obj_get_spi(struct bpf_verifier_env *env, struct bpf_reg_state *reg, const char *obj_kind, int nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f6a60)
Location: kernel/bpf/verifier.c:693
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff812f6a60-ffffffff812f6b2a: stack_slot_obj_get_spi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int stack_slot_obj_get_spi(struct bpf_verifier_env *env, struct bpf_reg_state *reg, const char *obj_kind, int nr_slots);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81315920)
Location: kernel/bpf/verifier.c:588
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_kfunc_args
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_iter_arg
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:process_dynptr_func
  - kernel/bpf/verifier.c:mark_stack_slots_dynptr
```
**Symbols:**

```
ffffffff81315920-ffffffff813159ea: stack_slot_obj_get_spi (STB_LOCAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
