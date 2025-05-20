# Function: <code>clean_live_states</code>

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
In kernel/bpf/verifier.c (ffffffff811cd642)
Location: kernel/bpf/verifier.c:5386
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
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
In kernel/bpf/verifier.c (ffffffff811e034c)
Location: kernel/bpf/verifier.c:6788
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811ecb17)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clean_live_states(struct bpf_verifier_env *env, int insn, struct bpf_verifier_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203660)
Location: kernel/bpf/verifier.c:7936
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81203660-ffffffff81203717: clean_live_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clean_live_states(struct bpf_verifier_env *env, int insn, struct bpf_verifier_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81203860)
Location: kernel/bpf/verifier.c:8724
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81203860-ffffffff81203917: clean_live_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clean_live_states(struct bpf_verifier_env *env, int insn, struct bpf_verifier_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812043c0)
Location: kernel/bpf/verifier.c:9895
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff812043c0-ffffffff81204572: clean_live_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clean_live_states(struct bpf_verifier_env *env, int insn, struct bpf_verifier_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81236a10)
Location: kernel/bpf/verifier.c:10226
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81236a10-ffffffff81236cd4: clean_live_states (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clean_live_states(struct bpf_verifier_env *env, int insn, struct bpf_verifier_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127b160)
Location: kernel/bpf/verifier.c:11283
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff8127b160-ffffffff8127b43f: clean_live_states (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff812e5b77)
Location: kernel/bpf/verifier.c:13255
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clean_live_states(struct bpf_verifier_env *env, int insn, struct bpf_verifier_state *cur);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812ffef0)
Location: kernel/bpf/verifier.c:15256
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff812ffef0-ffffffff8130020b: clean_live_states (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff813297d0)
Location: kernel/bpf/verifier.c:16301
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffff800010270444)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (c04a26cc)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (c000000000317430)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffe0001a9b1e)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811e5137)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811d7ef7)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811e2f07)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff811f12d7)
Location: kernel/bpf/verifier.c:6803
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
</ul>
