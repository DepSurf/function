# Function: <code>adjust_insn_aux_data</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811946af)
Location: kernel/bpf/verifier.c:3495
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a2b2f)
Location: kernel/bpf/verifier.c:4300
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
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
In kernel/bpf/verifier.c (ffffffff811b6f12)
Location: kernel/bpf/verifier.c:5201
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
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
In kernel/bpf/verifier.c (ffffffff811c60a3)
Location: kernel/bpf/verifier.c:6387
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811deba9)
Location: kernel/bpf/verifier.c:8079
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb369)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int adjust_insn_aux_data(struct bpf_verifier_env *env, struct bpf_prog *new_prog, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812032c0)
Location: kernel/bpf/verifier.c:9208
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff812032c0-ffffffff81203444: adjust_insn_aux_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int adjust_insn_aux_data(struct bpf_verifier_env *env, struct bpf_prog *new_prog, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203620)
Location: kernel/bpf/verifier.c:10125
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff81203620-ffffffff812037c8: adjust_insn_aux_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int adjust_insn_aux_data(struct bpf_verifier_env *env, struct bpf_prog *new_prog, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204220)
Location: kernel/bpf/verifier.c:11386
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff81204220-ffffffff812043be: adjust_insn_aux_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void adjust_insn_aux_data(struct bpf_verifier_env *env, struct bpf_insn_aux_data *new_data, struct bpf_prog *new_prog, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81236580)
Location: kernel/bpf/verifier.c:11764
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff81236580-ffffffff81236703: adjust_insn_aux_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void adjust_insn_aux_data(struct bpf_verifier_env *env, struct bpf_insn_aux_data *new_data, struct bpf_prog *new_prog, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127ab50)
Location: kernel/bpf/verifier.c:12823
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff8127ab50-ffffffff8127ace5: adjust_insn_aux_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void adjust_insn_aux_data(struct bpf_verifier_env *env, struct bpf_insn_aux_data *new_data, struct bpf_prog *new_prog, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d1240)
Location: kernel/bpf/verifier.c:14800
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff812d1240-ffffffff812d13c4: adjust_insn_aux_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void adjust_insn_aux_data(struct bpf_verifier_env *env, struct bpf_insn_aux_data *new_data, struct bpf_prog *new_prog, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fd060)
Location: kernel/bpf/verifier.c:17017
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff812fd060-ffffffff812fd1e4: adjust_insn_aux_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void adjust_insn_aux_data(struct bpf_verifier_env *env, struct bpf_insn_aux_data *new_data, struct bpf_prog *new_prog, u32 off, u32 cnt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131c580)
Location: kernel/bpf/verifier.c:18171
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff8131c580-ffffffff8131c704: adjust_insn_aux_data (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026ecb0)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04a106c)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000315574)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a8802)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e3989)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d6749)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1759)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811efb69)
Location: kernel/bpf/verifier.c:8094
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_insn_aux_data *new_data</code>
</li>
<li>
<b>Param reordered. </b>
<code>env, new_prog, off, cnt</code> ➡️ <code>env, new_data, new_prog, off, cnt</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
