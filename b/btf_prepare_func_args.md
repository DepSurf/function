# Function: <code>btf_prepare_func_args</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int btf_prepare_func_args(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81225990)
Location: kernel/bpf/btf.c:4471
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff81225990-ffffffff81225d55: btf_prepare_func_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int btf_prepare_func_args(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *reg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff8122c290)
Location: kernel/bpf/btf.c:5395
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff8122c290-ffffffff8122c75b: btf_prepare_func_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int btf_prepare_func_args(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/btf.c (ffffffff81230fb0)
Location: kernel/bpf/btf.c:5569
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff81230fb0-ffffffff81231514: btf_prepare_func_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int btf_prepare_func_args(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:5622
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff81cb9544-ffffffff81cb955f: btf_prepare_func_args.cold (STB_LOCAL)
ffffffff81269ef0-ffffffff8126a4a6: btf_prepare_func_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int btf_prepare_func_args(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6355
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff81e6a8b4-ffffffff81e6a8d9: btf_prepare_func_args.cold (STB_LOCAL)
ffffffff812b6c50-ffffffff812b726f: btf_prepare_func_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int btf_prepare_func_args(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6846
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff820619aa-ffffffff820619cf: btf_prepare_func_args.cold (STB_LOCAL)
ffffffff81318170-ffffffff813187a1: btf_prepare_func_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int btf_prepare_func_args(struct bpf_verifier_env *env, int subprog, struct bpf_reg_state *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6948
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff820e1060-ffffffff820e1085: btf_prepare_func_args.cold (STB_LOCAL)
ffffffff81348100-ffffffff81348756: btf_prepare_func_args (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int btf_prepare_func_args(struct bpf_verifier_env *env, int subprog);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/btf.c (0)
Location: kernel/bpf/btf.c:6957
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
```
**Symbols:**

```
ffffffff821bd856-ffffffff821bd892: btf_prepare_func_args.cold (STB_LOCAL)
ffffffff8136e390-ffffffff8136ee8b: btf_prepare_func_args (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_reg_state *regs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state *reg</code>
</li>
</ul>
</details>
</li>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bpf_reg_state *regs</code>
</li>
</ul>
</details>
</li>
</ul>
