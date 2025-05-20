# Function: <code>clean_func_state</code>

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
In kernel/bpf/verifier.c (ffffffff811cd6c2)
Location: kernel/bpf/verifier.c:5312
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
In kernel/bpf/verifier.c (ffffffff811e075d)
Location: kernel/bpf/verifier.c:6714
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
In kernel/bpf/verifier.c (ffffffff811ecf51)
Location: kernel/bpf/verifier.c:6729
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
void clean_func_state(struct bpf_verifier_env *env, struct bpf_func_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81202310)
Location: kernel/bpf/verifier.c:7862
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:clean_live_states
```
**Symbols:**

```
ffffffff81202310-ffffffff812023f4: clean_func_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clean_func_state(struct bpf_verifier_env *env, struct bpf_func_state *st);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81201ff0)
Location: kernel/bpf/verifier.c:8650
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:clean_live_states
```
**Symbols:**

```
ffffffff81201ff0-ffffffff812020d4: clean_func_state (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81204470)
Location: kernel/bpf/verifier.c:9821
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_live_states
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
In kernel/bpf/verifier.c (ffffffff81236b03)
Location: kernel/bpf/verifier.c:10152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_live_states
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
In kernel/bpf/verifier.c (ffffffff8127b263)
Location: kernel/bpf/verifier.c:11209
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_live_states
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
In kernel/bpf/verifier.c (ffffffff812e5efc)
Location: kernel/bpf/verifier.c:13181
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff812ffff9)
Location: kernel/bpf/verifier.c:15182
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:clean_live_states
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
In kernel/bpf/verifier.c (ffffffff81329896)
Location: kernel/bpf/verifier.c:16227
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
In kernel/bpf/verifier.c (ffff800010270870)
Location: kernel/bpf/verifier.c:6729
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
In kernel/bpf/verifier.c (c04a2b8c)
Location: kernel/bpf/verifier.c:6729
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
In kernel/bpf/verifier.c (c0000000003179e0)
Location: kernel/bpf/verifier.c:6729
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
In kernel/bpf/verifier.c (ffffffe0001a9b22)
Location: kernel/bpf/verifier.c:6729
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
In kernel/bpf/verifier.c (ffffffff811e5571)
Location: kernel/bpf/verifier.c:6729
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
In kernel/bpf/verifier.c (ffffffff811d8331)
Location: kernel/bpf/verifier.c:6729
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
In kernel/bpf/verifier.c (ffffffff811e3341)
Location: kernel/bpf/verifier.c:6729
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
In kernel/bpf/verifier.c (ffffffff811f1711)
Location: kernel/bpf/verifier.c:6729
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
</ul>
