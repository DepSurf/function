# Function: <code>check_stack_boundary</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_stack_boundary(struct verifier_env *env, int regno, int access_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81173bf0)
Location: kernel/bpf/verifier.c:781
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81173bf0-ffffffff81173c7b: check_stack_boundary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_stack_boundary(struct verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81181e90)
Location: kernel/bpf/verifier.c:885
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81181e90-ffffffff81181f70: check_stack_boundary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_stack_boundary(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8118e390)
Location: kernel/bpf/verifier.c:917
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff8118e390-ffffffff8118e470: check_stack_boundary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_stack_boundary(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811940e0)
Location: kernel/bpf/verifier.c:1023
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811940e0-ffffffff811941f3: check_stack_boundary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_stack_boundary(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a1d00)
Location: kernel/bpf/verifier.c:1306
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff811a1d00-ffffffff811a1f43: check_stack_boundary (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff811ba772)
Location: kernel/bpf/verifier.c:1844
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (ffffffff811ca2c6)
Location: kernel/bpf/verifier.c:2106
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (ffffffff811dd252)
Location: kernel/bpf/verifier.c:2962
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e99f2)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_stack_boundary(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81209150)
Location: kernel/bpf/verifier.c:3454
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff81209150-ffffffff8120958c: check_stack_boundary (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_stack_boundary(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120a620)
Location: kernel/bpf/verifier.c:3684
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
```
**Symbols:**

```
ffffffff8120a620-ffffffff8120aa11: check_stack_boundary (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/bpf/verifier.c (ffff80001026d230)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (c049f7c4)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (c000000000313a20)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (ffffffe0001a7342)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (ffffffff811e2012)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (ffffffff811d4dd2)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (ffffffff811dfde2)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
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
In kernel/bpf/verifier.c (ffffffff811ee1f2)
Location: kernel/bpf/verifier.c:2963
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:check_helper_mem_access
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool zero_size_allowed</code>
</li>
<li>
<b>Param added. </b>
<code>struct bpf_call_arg_meta *meta</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct verifier_env *env</code> ➡️ <code>struct bpf_verifier_env *env</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
