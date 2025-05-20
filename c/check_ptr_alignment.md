# Function: <code>check_ptr_alignment</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811823a9)
Location: kernel/bpf/verifier.c:712
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118ec46)
Location: kernel/bpf/verifier.c:713
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81194ecb)
Location: kernel/bpf/verifier.c:850
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a2930)
Location: kernel/bpf/verifier.c:1054
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811a2930-ffffffff811a2afa: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b9abf)
Location: kernel/bpf/verifier.c:1493
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c947e)
Location: kernel/bpf/verifier.c:1746
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dca50)
Location: kernel/bpf/verifier.c:2526
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811dca50-ffffffff811dccef: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e91f0)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e91f0-ffffffff811e948f: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208760)
Location: kernel/bpf/verifier.c:2875
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81208760-ffffffff812089ff: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812092f0)
Location: kernel/bpf/verifier.c:2959
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812092f0-ffffffff8120954b: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120be00)
Location: kernel/bpf/verifier.c:3499
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8120be00-ffffffff8120c06e: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3574
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8123fc80-ffffffff8123ff1a: check_ptr_alignment (STB_LOCAL)
ffffffff81cb84bc-ffffffff81cb84d8: check_ptr_alignment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4125
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81284d50-ffffffff81285015: check_ptr_alignment (STB_LOCAL)
ffffffff81e696ab-ffffffff81e696c7: check_ptr_alignment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4580
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812d6fd0-ffffffff812d7295: check_ptr_alignment (STB_LOCAL)
ffffffff82060049-ffffffff82060065: check_ptr_alignment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5505
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812f97c0-ffffffff812f9a7d: check_ptr_alignment (STB_LOCAL)
ffffffff820dec17-ffffffff820dec33: check_ptr_alignment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5720
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81319290-ffffffff8131954d: check_ptr_alignment (STB_LOCAL)
ffffffff821baccb-ffffffff821bace7: check_ptr_alignment.cold (STB_LOCAL)
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
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026c900)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffff80001026c900-ffff80001026cb88: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049ee54)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c049ee54-c049f164: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000312f10)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c000000000312f10-c000000000313208: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a6c7c)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffe0001a6c7c-ffffffe0001a6e0e: check_ptr_alignment (STB_LOCAL)
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
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1810)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811e1810-ffffffff811e1aaf: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d45d0)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811d45d0-ffffffff811d486f: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811df5e0)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811df5e0-ffffffff811df87f: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_ptr_alignment(struct bpf_verifier_env *env, const struct bpf_reg_state *reg, int off, int size, bool strict_alignment_once);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ed9f0)
Location: kernel/bpf/verifier.c:2527
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff811ed9f0-ffffffff811edc8f: check_ptr_alignment (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
