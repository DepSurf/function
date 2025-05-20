# Function: <code>free_func_state</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811bd75d)
Location: kernel/bpf/verifier.c:421
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffff811b7020-ffffffff811b7044: free_func_state.part.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cec87)
Location: kernel/bpf/verifier.c:661
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffff811c61b0-ffffffff811c61e0: free_func_state.part.35 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e3994)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffff811d7bd0-ffffffff811d7c03: free_func_state.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811f0203)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffff811e42c0-ffffffff811e42f3: free_func_state.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff8120cf7b)
Location: kernel/bpf/verifier.c:794
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8120b21b)
Location: kernel/bpf/verifier.c:820
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
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
In kernel/bpf/verifier.c (ffffffff812104d6)
Location: kernel/bpf/verifier.c:869
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
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
In kernel/bpf/verifier.c (ffffffff81244d45)
Location: kernel/bpf/verifier.c:885
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8128a80e)
Location: kernel/bpf/verifier.c:1112
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
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
In kernel/bpf/verifier.c (ffffffff812e2d0e)
Location: kernel/bpf/verifier.c:1314
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8130687e)
Location: kernel/bpf/verifier.c:1691
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
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
In kernel/bpf/verifier.c (ffffffff8132b74e)
Location: kernel/bpf/verifier.c:1344
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:prepare_func_exit
  - kernel/bpf/verifier.c:setup_func_entry
  - kernel/bpf/verifier.c:setup_func_entry
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
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
In kernel/bpf/verifier.c (ffff8000102738d4)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffff800010267458-ffff800010267494: free_func_state.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (c04a6034)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
c04997bc-c04997f0: free_func_state.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (c00000000031b508)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
c00000000030ca80-c00000000030cadc: free_func_state.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffe0001ac654)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffe0001a27e4-ffffffe0001a2826: free_func_state.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e8823)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffff811dc8e0-ffffffff811dc913: free_func_state.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811db5e3)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffff811cf6a0-ffffffff811cf6d3: free_func_state.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811e65f3)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffff811da6b0-ffffffff811da6e3: free_func_state.part.0 (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811f49b1)
Location: kernel/bpf/verifier.c:667
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:copy_verifier_state
  - kernel/bpf/verifier.c:free_verifier_state
```
**Symbols:**

```
ffffffff811e8ac0-ffffffff811e8af3: free_func_state.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
