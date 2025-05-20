# Function: <code>free_verifier_state</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a8212)
Location: kernel/bpf/verifier.c:344
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:pop_stack
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b7050)
Location: kernel/bpf/verifier.c:429
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811b7050-ffffffff811b70a2: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c61e0)
Location: kernel/bpf/verifier.c:670
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811c61e0-ffffffff811c6232: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d7c10)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811d7c10-ffffffff811d7c7e: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e4300)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811e4300-ffffffff811e436e: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203450)
Location: kernel/bpf/verifier.c:810
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff81203450-ffffffff812034df: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812037d0)
Location: kernel/bpf/verifier.c:836
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff812037d0-ffffffff8120385f: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204190)
Location: kernel/bpf/verifier.c:885
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff81204190-ffffffff8120421f: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812364b0)
Location: kernel/bpf/verifier.c:901
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff812364b0-ffffffff8123657a: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127aa70)
Location: kernel/bpf/verifier.c:1128
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff8127aa70-ffffffff8127ab4a: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d1690)
Location: kernel/bpf/verifier.c:1330
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff812d1690-ffffffff812d176d: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fe1d0)
Location: kernel/bpf/verifier.c:1707
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:__check_func_call
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff812fe1d0-ffffffff812fe2ad: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131d820)
Location: kernel/bpf/verifier.c:1360
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_callback_call
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff8131d820-ffffffff8131d903: free_verifier_state (STB_LOCAL)
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
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010267498)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffff800010267498-ffff80001026751c: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c04997f0)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
c04997f0-c0499860: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030cae0)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
c00000000030cae0-c00000000030cbd0: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a2826)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffe0001a2826-ffffffe0001a28a6: free_verifier_state (STB_LOCAL)
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
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dc920)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811dc920-ffffffff811dc98e: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811cf6e0)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811cf6e0-ffffffff811cf74e: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da6f0)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811da6f0-ffffffff811da75e: free_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_verifier_state(struct bpf_verifier_state *state, bool free_self);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e8b00)
Location: kernel/bpf/verifier.c:683
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811e8b00-ffffffff811e8b6e: free_verifier_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
