# Function: <code>check_stack_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8117410e)
Location: kernel/bpf/verifier.c:595
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81182656)
Location: kernel/bpf/verifier.c:601
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
In kernel/bpf/verifier.c (ffffffff8118ef89)
Location: kernel/bpf/verifier.c:584
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
In kernel/bpf/verifier.c (ffffffff81194f7d)
Location: kernel/bpf/verifier.c:605
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811a5912)
Location: kernel/bpf/verifier.c:753
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811b9dfd)
Location: kernel/bpf/verifier.c:1164
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
In kernel/bpf/verifier.c (ffffffff811c9a61)
Location: kernel/bpf/verifier.c:1321
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e1214)
Location: kernel/bpf/verifier.c:2012
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811eda14)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_stack_read(struct bpf_verifier_env *env, struct bpf_func_state *reg_state, int off, int size, int value_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120f3f0)
Location: kernel/bpf/verifier.c:2332
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8120f3f0-ffffffff8120f6ee: check_stack_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_stack_read(struct bpf_verifier_env *env, struct bpf_func_state *reg_state, int off, int size, int value_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210ad0)
Location: kernel/bpf/verifier.c:2405
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81210ad0-ffffffff81210dce: check_stack_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_stack_read(struct bpf_verifier_env *env, int ptr_regno, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812123c0)
Location: kernel/bpf/verifier.c:2988
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812123c0-ffffffff81212546: check_stack_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_stack_read(struct bpf_verifier_env *env, int ptr_regno, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3054
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81247aa0-ffffffff81247d39: check_stack_read (STB_LOCAL)
ffffffff81cb8ae6-ffffffff81cb8b2d: check_stack_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_stack_read(struct bpf_verifier_env *env, int ptr_regno, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3417
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8128dd00-ffffffff8128dfd2: check_stack_read (STB_LOCAL)
ffffffff81e69d67-ffffffff81e69dae: check_stack_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_stack_read(struct bpf_verifier_env *env, int ptr_regno, int off, int size, int dst_regno);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:3859
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff812e5130-ffffffff812e5402: check_stack_read (STB_LOCAL)
ffffffff82060b58-ffffffff82060b9f: check_stack_read.cold (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81312e72)
Location: kernel/bpf/verifier.c:4748
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff81332d7a)
Location: kernel/bpf/verifier.c:4906
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffff8000102716f0)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (c04a39d8)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (c000000000318b94)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffe0001aaa6c)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e6034)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811d8df4)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e3e04)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
In kernel/bpf/verifier.c (ffffffff811f21d4)
Location: kernel/bpf/verifier.c:2013
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_mem_access
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int ptr_regno</code>
</li>
<li>
<b>Param added. </b>
<code>int dst_regno</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_func_state *reg_state</code>
</li>
<li>
<b>Param removed. </b>
<code>int value_regno</code>
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
</ul>
