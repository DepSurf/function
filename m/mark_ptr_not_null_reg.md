# Function: <code>mark_ptr_not_null_reg</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mark_ptr_not_null_reg(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202f10)
Location: kernel/bpf/verifier.c:1125
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_reg
```
**Symbols:**

```
ffffffff81202f10-ffffffff81202fd3: mark_ptr_not_null_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mark_ptr_not_null_reg(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1134
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_reg
```
**Symbols:**

```
ffffffff81235d60-ffffffff81235e47: mark_ptr_not_null_reg (STB_LOCAL)
ffffffff81cb7c25-ffffffff81cb7c39: mark_ptr_not_null_reg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mark_ptr_not_null_reg(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81279cf0)
Location: kernel/bpf/verifier.c:1361
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_mem_reg
```
**Symbols:**

```
ffffffff81279cf0-ffffffff81279d80: mark_ptr_not_null_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mark_ptr_not_null_reg(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d0540)
Location: kernel/bpf/verifier.c:1575
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_mem_reg
```
**Symbols:**

```
ffffffff812d0540-ffffffff812d05e0: mark_ptr_not_null_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mark_ptr_not_null_reg(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fa640)
Location: kernel/bpf/verifier.c:1956
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_mem_reg
```
**Symbols:**

```
ffffffff812fa640-ffffffff812fa6e0: mark_ptr_not_null_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mark_ptr_not_null_reg(struct bpf_reg_state *reg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81319f80)
Location: kernel/bpf/verifier.c:1810
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:check_kfunc_mem_size_reg
  - kernel/bpf/verifier.c:check_mem_reg
```
**Symbols:**

```
ffffffff81319f80-ffffffff8131a020: mark_ptr_not_null_reg (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
