# Function: <code>copy_verifier_state</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a4bb0)
Location: kernel/bpf/verifier.c:355
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811a4bb0-ffffffff811a4c98: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b76a0)
Location: kernel/bpf/verifier.c:457
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_cond_jmp_op
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811b76a0-ffffffff811b7833: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c6c20)
Location: kernel/bpf/verifier.c:702
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811c6c20-ffffffff811c6e09: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d8e20)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811d8e20-ffffffff811d90ad: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e5510)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811e5510-ffffffff811e579d: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204ae0)
Location: kernel/bpf/verifier.c:843
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff81204ae0-ffffffff81204d71: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81204aa0)
Location: kernel/bpf/verifier.c:869
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff81204aa0-ffffffff81204d31: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812049b0)
Location: kernel/bpf/verifier.c:918
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff812049b0-ffffffff81204c3d: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:930
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff81236770-ffffffff81236a0b: copy_verifier_state (STB_LOCAL)
ffffffff81cb7c4d-ffffffff81cb7c61: copy_verifier_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1157
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff8127acf0-ffffffff8127afb4: copy_verifier_state (STB_LOCAL)
ffffffff81e68dec-ffffffff81e68e00: copy_verifier_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1359
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff812d1890-ffffffff812d1aaa: copy_verifier_state (STB_LOCAL)
ffffffff8205fb41-ffffffff8205fb69: copy_verifier_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1736
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff812feca0-ffffffff812feeba: copy_verifier_state (STB_LOCAL)
ffffffff820def1c-ffffffff820def44: copy_verifier_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:1389
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:push_stack
```
**Symbols:**

```
ffffffff8131e380-ffffffff8131e610: copy_verifier_state (STB_LOCAL)
ffffffff821bb014-ffffffff821bb050: copy_verifier_state.cold (STB_LOCAL)
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
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff800010268668)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffff800010268668-ffff800010268924: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049aabc)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
c049aabc-c049ad88: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030e2f0)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
c00000000030e2f0-c00000000030e670: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a387a)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffe0001a387a-ffffffe0001a3aea: copy_verifier_state (STB_LOCAL)
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
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ddb30)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811ddb30-ffffffff811dddbd: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d08f0)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811d08f0-ffffffff811d0b7d: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db900)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811db900-ffffffff811dbb8d: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_verifier_state(struct bpf_verifier_state *dst_state, const struct bpf_verifier_state *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9d10)
Location: kernel/bpf/verifier.c:716
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:pop_stack
```
**Symbols:**

```
ffffffff811e9d10-ffffffff811e9f9d: copy_verifier_state (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_verifier_state *dst_state</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bpf_verifier_state *dst</code>
</li>
</ul>
</details>
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
