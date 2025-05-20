# Function: <code>__check_ptr_off_reg</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int __check_ptr_off_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno, bool fixed_off_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127d230)
Location: kernel/bpf/verifier.c:3615
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff8127d230-ffffffff8127d34b: __check_ptr_off_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __check_ptr_off_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno, bool fixed_off_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d5870)
Location: kernel/bpf/verifier.c:4057
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff812d5870-ffffffff812d598b: __check_ptr_off_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __check_ptr_off_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno, bool fixed_off_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812f7540)
Location: kernel/bpf/verifier.c:4942
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff812f7540-ffffffff812f7658: __check_ptr_off_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __check_ptr_off_reg(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int regno, bool fixed_off_ok);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81316e20)
Location: kernel/bpf/verifier.c:5100
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_func_arg_reg_off
  - kernel/bpf/verifier.c:check_mem_access
  - kernel/bpf/verifier.c:map_kptr_match_type
```
**Symbols:**

```
ffffffff81316e20-ffffffff81316f38: __check_ptr_off_reg (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
