# Function: <code>copy_reference_state</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c5ff0)
Location: kernel/bpf/verifier.c:531
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811c5ff0-ffffffff811c6061: copy_reference_state.isra.32 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811d7b60)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811d7b60-ffffffff811d7bd0: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e4250)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811e4250-ffffffff811e42c0: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81203250)
Location: kernel/bpf/verifier.c:681
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff81203250-ffffffff812032c0: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff812030f0)
Location: kernel/bpf/verifier.c:707
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff812030f0-ffffffff81203160: copy_reference_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203c90)
Location: kernel/bpf/verifier.c:756
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff81203c90-ffffffff81203cfd: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81244ce4)
Location: kernel/bpf/verifier.c:795
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8128a7af)
Location: kernel/bpf/verifier.c:1022
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
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
In kernel/bpf/verifier.c (ffffffff812e2df7)
Location: kernel/bpf/verifier.c:1220
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_func_state
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
In kernel/bpf/verifier.c (ffffffff81306967)
Location: kernel/bpf/verifier.c:1597
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_func_state
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
In kernel/bpf/verifier.c (ffffffff8132b85b)
Location: kernel/bpf/verifier.c:1238
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:setup_func_entry
  - kernel/bpf/verifier.c:copy_func_state
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
In kernel/bpf/verifier.c (ffff8000102673c0)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffff8000102673c0-ffff800010267438: copy_reference_state.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_reference_state(struct bpf_func_state *dst, const struct bpf_func_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0499680)
Location: kernel/bpf/verifier.c:554
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
c0499680-c0499718: copy_reference_state (STB_LOCAL)
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
In kernel/bpf/verifier.c (c00000000030c9f0)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
c00000000030c9f0-c00000000030ca7c: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffe0001a2924)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffe0001a2924-ffffffe0001a2994: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811dc870)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811dc870-ffffffff811dc8e0: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811cf630)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811cf630-ffffffff811cf6a0: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811da640)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811da640-ffffffff811da6b0: copy_reference_state.isra.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e8a50)
Location: kernel/bpf/verifier.c:554
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:copy_verifier_state
```
**Symbols:**

```
ffffffff811e8a50-ffffffff811e8ac0: copy_reference_state.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
