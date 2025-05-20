# Function: <code>mark_reg_not_init</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811945b0)
Location: kernel/bpf/verifier.c:466
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811945b0-ffffffff81194610: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a34b0)
Location: kernel/bpf/verifier.c:585
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
```
**Symbols:**

```
ffffffff811a34b0-ffffffff811a359c: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b7cc0)
Location: kernel/bpf/verifier.c:713
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811b7cc0-ffffffff811b7db6: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6900)
Location: kernel/bpf/verifier.c:964
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811c6900-ffffffff811c6933: mark_reg_not_init.part.46 (STB_LOCAL)
ffffffff811c7180-ffffffff811c71ca: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e547d)
Location: kernel/bpf/verifier.c:1027
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811d9f70-ffffffff811d9fb1: mark_reg_not_init (STB_LOCAL)
ffffffff811e5450-ffffffff811e549a: mark_reg_not_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6670)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811e6670-ffffffff811e66f6: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206950)
Location: kernel/bpf/verifier.c:1340
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff81206950-ffffffff812069c5: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206720)
Location: kernel/bpf/verifier.c:1370
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff81206720-ffffffff81206795: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208680)
Location: kernel/bpf/verifier.c:1462
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff81208680-ffffffff812086f5: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8123c080)
Location: kernel/bpf/verifier.c:1482
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff8123c080-ffffffff8123c0f5: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81281bd0)
Location: kernel/bpf/verifier.c:1685
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff81281bd0-ffffffff81281c4c: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d9930)
Location: kernel/bpf/verifier.c:1899
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff812d9930-ffffffff812d99ac: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fae10)
Location: kernel/bpf/verifier.c:2298
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff812fae10-ffffffff812fae8c: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131a5c0)
Location: kernel/bpf/verifier.c:2304
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_kfunc_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff8131a5c0-ffffffff8131a63c: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff8000102680a0)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffff8000102680a0-ffff8000102680fc: mark_reg_not_init.part.0 (STB_LOCAL)
ffff800010269e38-ffff800010269ec8: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049be8c)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
c049be8c-c049bf20: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030f950)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
c00000000030f950-c00000000030fa18: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a33e8)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffe0001a33e8-ffffffe0001a3440: mark_reg_not_init.part.0 (STB_LOCAL)
ffffffe0001a4704-ffffffe0001a4790: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dec90)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811dec90-ffffffff811ded16: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d1a50)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811d1a50-ffffffff811d1ad6: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dca60)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811dca60-ffffffff811dcae6: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mark_reg_not_init(struct bpf_verifier_env *env, struct bpf_reg_state *regs, u32 regno);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eae70)
Location: kernel/bpf/verifier.c:1028
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
  - kernel/bpf/verifier.c:init_reg_state
```
**Symbols:**

```
ffffffff811eae70-ffffffff811eaef6: mark_reg_not_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_env *env</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, regno</code> ➡️ <code>env, regs, regno</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
