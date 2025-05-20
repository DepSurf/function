# Function: <code>find_subprog</code>

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
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b6900)
Location: kernel/bpf/verifier.c:770
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811b6900-ffffffff811b6950: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c5af0)
Location: kernel/bpf/verifier.c:1022
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811c5af0-ffffffff811c5b46: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d69a0)
Location: kernel/bpf/verifier.c:1087
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811d69a0-ffffffff811d69f6: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3080)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e3080-ffffffff811e30d6: find_subprog (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8120b611)
Location: kernel/bpf/verifier.c:1396
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_max_stack_depth
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
In kernel/bpf/verifier.c (ffffffff8120d81b)
Location: kernel/bpf/verifier.c:1441
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_max_stack_depth
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
In kernel/bpf/verifier.c (ffffffff8120f45b)
Location: kernel/bpf/verifier.c:1533
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_max_stack_depth
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
In kernel/bpf/verifier.c (ffffffff81243d95)
Location: kernel/bpf/verifier.c:1601
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_max_stack_depth
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
In kernel/bpf/verifier.c (ffffffff812897c3)
Location: kernel/bpf/verifier.c:1806
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_max_stack_depth
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
In kernel/bpf/verifier.c (ffffffff812e01e3)
Location: kernel/bpf/verifier.c:2021
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_max_stack_depth
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
In kernel/bpf/verifier.c (ffffffff8130a373)
Location: kernel/bpf/verifier.c:2420
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_max_stack_depth_subprog
  - kernel/bpf/verifier.c:backtrack_insn
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
In kernel/bpf/verifier.c (ffffffff8132ce45)
Location: kernel/bpf/verifier.c:2431
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:check_ld_imm
  - kernel/bpf/verifier.c:check_max_stack_depth_subprog
  - kernel/bpf/verifier.c:backtrack_insn
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010266338)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffff800010266338-ffff8000102663a0: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04987f4)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
c04987f4-c0498860: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030b040)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
c00000000030b040-c00000000030b0d4: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a178e)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffe0001a178e-ffffffe0001a17ec: find_subprog (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db6a0)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811db6a0-ffffffff811db6f6: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ce460)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811ce460-ffffffff811ce4b6: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d9470)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811d9470-ffffffff811d94c6: find_subprog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int find_subprog(struct bpf_verifier_env *env, int off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7880)
Location: kernel/bpf/verifier.c:1088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:jit_subprogs
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811e7880-ffffffff811e78d6: find_subprog (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
