# Function: <code>sanitize_val_alu</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c5950)
Location: kernel/bpf/verifier.c:3132
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
  - kernel/bpf/verifier.c:adjust_reg_min_max_vals
```
**Symbols:**

```
ffffffff811c5950-ffffffff811c59a4: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6800)
Location: kernel/bpf/verifier.c:4255
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811d6800-ffffffff811d6854: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e2ee0)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e2ee0-ffffffff811e2f34: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203200)
Location: kernel/bpf/verifier.c:4935
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff81203200-ffffffff81203249: sanitize_val_alu.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812030a0)
Location: kernel/bpf/verifier.c:5446
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff812030a0-ffffffff812030f0: sanitize_val_alu.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81209ace)
Location: kernel/bpf/verifier.c:6447
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff8123d7f4)
Location: kernel/bpf/verifier.c:6736
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff81283218)
Location: kernel/bpf/verifier.c:7735
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff812dad58)
Location: kernel/bpf/verifier.c:9671
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff813104a6)
Location: kernel/bpf/verifier.c:11587
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
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
In kernel/bpf/verifier.c (ffffffff81331036)
Location: kernel/bpf/verifier.c:12521
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
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
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff8000102662a0)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffff8000102662a0-ffff800010266338: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04981f4)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c04981f4-c049827c: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030afb0)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
c00000000030afb0-c00000000030b038: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a1718)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffe0001a1718-ffffffe0001a178e: sanitize_val_alu (STB_LOCAL)
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
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db500)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811db500-ffffffff811db554: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ce2c0)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811ce2c0-ffffffff811ce314: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d92d0)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811d92d0-ffffffff811d9324: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sanitize_val_alu(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e76e0)
Location: kernel/bpf/verifier.c:4258
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
  - kernel/bpf/verifier.c:adjust_scalar_min_max_vals
```
**Symbols:**

```
ffffffff811e76e0-ffffffff811e7734: sanitize_val_alu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
