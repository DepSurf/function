# Function: <code>mark_stack_slots_dynptr</code>

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
In kernel/bpf/verifier.c (ffffffff8129192f)
Location: kernel/bpf/verifier.c:691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mark_stack_slots_dynptr(struct bpf_verifier_env *env, struct bpf_reg_state *reg, enum bpf_arg_type arg_type, int insn_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d7db0)
Location: kernel/bpf/verifier.c:775
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812d7db0-ffffffff812d7fc2: mark_stack_slots_dynptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mark_stack_slots_dynptr(struct bpf_verifier_env *env, struct bpf_reg_state *reg, enum bpf_arg_type arg_type, int insn_idx, int clone_ref_obj_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81307190)
Location: kernel/bpf/verifier.c:881
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:process_dynptr_func
```
**Symbols:**

```
ffffffff81307190-ffffffff81307463: mark_stack_slots_dynptr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mark_stack_slots_dynptr(struct bpf_verifier_env *env, struct bpf_reg_state *reg, enum bpf_arg_type arg_type, int insn_idx, int clone_ref_obj_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff813264c0)
Location: kernel/bpf/verifier.c:690
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:process_dynptr_func
```
**Symbols:**

```
ffffffff813264c0-ffffffff81326793: mark_stack_slots_dynptr (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int clone_ref_obj_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
