# Function: <code>release_reference_state</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cb4ef)
Location: kernel/bpf/verifier.c:638
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_call
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d7610)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811d7610-ffffffff811d7674: release_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e3c70)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e3c70-ffffffff811e3cd4: release_reference_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202470)
Location: kernel/bpf/verifier.c:764
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81202470-ffffffff812024de: release_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812020e0)
Location: kernel/bpf/verifier.c:790
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812020e0-ffffffff8120214c: release_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812030c0)
Location: kernel/bpf/verifier.c:839
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
```
**Symbols:**

```
ffffffff812030c0-ffffffff8120312c: release_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81235070)
Location: kernel/bpf/verifier.c:867
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81235070-ffffffff812350dc: release_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81278c80)
Location: kernel/bpf/verifier.c:1094
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:release_reference
```
**Symbols:**

```
ffffffff81278c80-ffffffff81278d10: release_reference_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1293
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
```
**Symbols:**

```
ffffffff812cf9f0-ffffffff812cfadd: release_reference_state (STB_LOCAL)
ffffffff8205fa6a-ffffffff8205fa86: release_reference_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1670
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
```
**Symbols:**

```
ffffffff812f96c0-ffffffff812f97ae: release_reference_state (STB_LOCAL)
ffffffff820debfb-ffffffff820dec17: release_reference_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1323
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
```
**Symbols:**

```
ffffffff81318360-ffffffff8131844e: release_reference_state (STB_LOCAL)
ffffffff821bab0c-ffffffff821bab28: release_reference_state.cold (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff800010266ab8)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffff800010266ab8-ffff800010266b74: release_reference_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int release_reference_state(struct bpf_func_state *state, int ptr_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04995dc)
Location: kernel/bpf/verifier.c:637
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c04995dc-c0499680: release_reference_state (STB_LOCAL)
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
In kernel/bpf/verifier.c (c00000000030bfd0)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c00000000030bfd0-c00000000030c088: release_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffe0001a2994)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffe0001a2994-ffffffe0001a2a76: release_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811dc290)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811dc290-ffffffff811dc2f4: release_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811cf050)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811cf050-ffffffff811cf0b4: release_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811da060)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811da060-ffffffff811da0c4: release_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e8470)
Location: kernel/bpf/verifier.c:637
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:mark_ptr_or_null_regs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e8470-ffffffff811e84d4: release_reference_state.isra.0 (STB_LOCAL)
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
</ul>
