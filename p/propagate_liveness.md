# Function: <code>propagate_liveness</code>

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
In kernel/bpf/verifier.c (ffffffff811a69cd)
Location: kernel/bpf/verifier.c:3756
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
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
In kernel/bpf/verifier.c (ffffffff811bd432)
Location: kernel/bpf/verifier.c:4575
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check
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
In kernel/bpf/verifier.c (ffffffff811ced24)
Location: kernel/bpf/verifier.c:5676
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
In kernel/bpf/verifier.c (ffffffff811e087b)
Location: kernel/bpf/verifier.c:7120
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
In kernel/bpf/verifier.c (ffffffff811ed073)
Location: kernel/bpf/verifier.c:7135
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
int propagate_liveness(struct bpf_verifier_env *env, const struct bpf_verifier_state *vstate, struct bpf_verifier_state *vparent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206d80)
Location: kernel/bpf/verifier.c:8268
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81206d80-ffffffff81206f73: propagate_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int propagate_liveness(struct bpf_verifier_env *env, const struct bpf_verifier_state *vstate, struct bpf_verifier_state *vparent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206b50)
Location: kernel/bpf/verifier.c:9056
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81206b50-ffffffff81206d51: propagate_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int propagate_liveness(struct bpf_verifier_env *env, const struct bpf_verifier_state *vstate, struct bpf_verifier_state *vparent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206c00)
Location: kernel/bpf/verifier.c:10220
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81206c00-ffffffff81206dce: propagate_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int propagate_liveness(struct bpf_verifier_env *env, const struct bpf_verifier_state *vstate, struct bpf_verifier_state *vparent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81239f50)
Location: kernel/bpf/verifier.c:10551
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff81239f50-ffffffff8123a165: propagate_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int propagate_liveness(struct bpf_verifier_env *env, const struct bpf_verifier_state *vstate, struct bpf_verifier_state *vparent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127e080)
Location: kernel/bpf/verifier.c:11607
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff8127e080-ffffffff8127e2ea: propagate_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int propagate_liveness(struct bpf_verifier_env *env, const struct bpf_verifier_state *vstate, struct bpf_verifier_state *vparent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d67a0)
Location: kernel/bpf/verifier.c:13603
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff812d67a0-ffffffff812d69fc: propagate_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int propagate_liveness(struct bpf_verifier_env *env, const struct bpf_verifier_state *vstate, struct bpf_verifier_state *vparent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fcdf0)
Location: kernel/bpf/verifier.c:15652
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff812fcdf0-ffffffff812fd043: propagate_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int propagate_liveness(struct bpf_verifier_env *env, const struct bpf_verifier_state *vstate, struct bpf_verifier_state *vparent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8131c310)
Location: kernel/bpf/verifier.c:16710
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff8131c310-ffffffff8131c563: propagate_liveness (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffff8000102709f8)
Location: kernel/bpf/verifier.c:7135
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
In kernel/bpf/verifier.c (c04a2cb8)
Location: kernel/bpf/verifier.c:7135
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
In kernel/bpf/verifier.c (c000000000317bf0)
Location: kernel/bpf/verifier.c:7135
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
In kernel/bpf/verifier.c (ffffffe0001a9ff4)
Location: kernel/bpf/verifier.c:7135
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
In kernel/bpf/verifier.c (ffffffff811e5693)
Location: kernel/bpf/verifier.c:7135
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
In kernel/bpf/verifier.c (ffffffff811d8453)
Location: kernel/bpf/verifier.c:7135
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
In kernel/bpf/verifier.c (ffffffff811e3463)
Location: kernel/bpf/verifier.c:7135
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
In kernel/bpf/verifier.c (ffffffff811f1833)
Location: kernel/bpf/verifier.c:7135
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
