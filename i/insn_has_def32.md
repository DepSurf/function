# Function: <code>insn_has_def32</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d8900)
Location: kernel/bpf/verifier.c:1337
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811d8900-ffffffff811d8932: insn_has_def32.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4ff0)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811e4ff0-ffffffff811e5022: insn_has_def32.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8120330e)
Location: kernel/bpf/verifier.c:1647
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
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
In kernel/bpf/verifier.c (ffffffff81203675)
Location: kernel/bpf/verifier.c:1699
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
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
In kernel/bpf/verifier.c (ffffffff81204283)
Location: kernel/bpf/verifier.c:1988
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
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
In kernel/bpf/verifier.c (ffffffff812365e8)
Location: kernel/bpf/verifier.c:2056
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
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
In kernel/bpf/verifier.c (ffffffff8127abbd)
Location: kernel/bpf/verifier.c:2399
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
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
In kernel/bpf/verifier.c (ffffffff812d12a6)
Location: kernel/bpf/verifier.c:2640
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
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
In kernel/bpf/verifier.c (ffffffff812fd0c6)
Location: kernel/bpf/verifier.c:3090
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
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
In kernel/bpf/verifier.c (ffffffff8131c5e6)
Location: kernel/bpf/verifier.c:3190
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:adjust_insn_aux_data
  - kernel/bpf/verifier.c:adjust_insn_aux_data
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010268210)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffff800010268210-ffff800010268274: insn_has_def32.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool insn_has_def32(struct bpf_verifier_env *env, struct bpf_insn *insn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049a69c)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
c049a69c-c049a6f4: insn_has_def32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030dd00)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
c00000000030dd00-c00000000030dd78: insn_has_def32.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a350c)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffe0001a350c-ffffffe0001a356c: insn_has_def32.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dd610)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811dd610-ffffffff811dd642: insn_has_def32.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d03d0)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811d03d0-ffffffff811d0402: insn_has_def32.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db3e0)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811db3e0-ffffffff811db412: insn_has_def32.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e97f0)
Location: kernel/bpf/verifier.c:1338
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:bpf_patch_insn_data
  - kernel/bpf/verifier.c:bpf_patch_insn_data
```
**Symbols:**

```
ffffffff811e97f0-ffffffff811e9822: insn_has_def32.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
