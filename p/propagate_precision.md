# Function: <code>propagate_precision</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e0a0b)
Location: kernel/bpf/verifier.c:7167
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
In kernel/bpf/verifier.c (ffffffff811ed205)
Location: kernel/bpf/verifier.c:7182
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
int propagate_precision(struct bpf_verifier_env *env, const struct bpf_verifier_state *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c5d0)
Location: kernel/bpf/verifier.c:8315
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff8120c5d0-ffffffff8120c6ca: propagate_precision (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int propagate_precision(struct bpf_verifier_env *env, const struct bpf_verifier_state *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81207b20)
Location: kernel/bpf/verifier.c:9103
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81207b20-ffffffff81207c1a: propagate_precision (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81211f74)
Location: kernel/bpf/verifier.c:10267
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff81247297)
Location: kernel/bpf/verifier.c:10598
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
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
In kernel/bpf/verifier.c (ffffffff8128d385)
Location: kernel/bpf/verifier.c:11654
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:is_state_visited
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int propagate_precision(struct bpf_verifier_env *env, const struct bpf_verifier_state *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:13650
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff812d99c0-ffffffff812d9b4f: propagate_precision (STB_LOCAL)
ffffffff82060199-ffffffff820601c9: propagate_precision.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int propagate_precision(struct bpf_verifier_env *env, const struct bpf_verifier_state *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:15699
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff8130d040-ffffffff8130d2ba: propagate_precision (STB_LOCAL)
ffffffff820dfb17-ffffffff820dfb99: propagate_precision.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int propagate_precision(struct bpf_verifier_env *env, const struct bpf_verifier_state *old);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:16757
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81329490-ffffffff8132970a: propagate_precision (STB_LOCAL)
ffffffff821bbae1-ffffffff821bbb63: propagate_precision.cold (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff800010270b80)
Location: kernel/bpf/verifier.c:7182
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
In kernel/bpf/verifier.c (c04a2e08)
Location: kernel/bpf/verifier.c:7182
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
In kernel/bpf/verifier.c (c000000000317db8)
Location: kernel/bpf/verifier.c:7182
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
In kernel/bpf/verifier.c (ffffffe0001aa15e)
Location: kernel/bpf/verifier.c:7182
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
In kernel/bpf/verifier.c (ffffffff811e5825)
Location: kernel/bpf/verifier.c:7182
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
In kernel/bpf/verifier.c (ffffffff811d85e5)
Location: kernel/bpf/verifier.c:7182
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
In kernel/bpf/verifier.c (ffffffff811e35f5)
Location: kernel/bpf/verifier.c:7182
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
In kernel/bpf/verifier.c (ffffffff811f19c5)
Location: kernel/bpf/verifier.c:7182
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
