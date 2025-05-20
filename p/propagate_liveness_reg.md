# Function: <code>propagate_liveness_reg</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da150)
Location: kernel/bpf/verifier.c:7087
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff811da150-ffffffff811da1a2: propagate_liveness_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e68f0)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff811e68f0-ffffffff811e6942: propagate_liveness_reg (STB_LOCAL)
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
In kernel/bpf/verifier.c (ffffffff81206e59)
Location: kernel/bpf/verifier.c:8235
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
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
In kernel/bpf/verifier.c (ffffffff81206c34)
Location: kernel/bpf/verifier.c:9023
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
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
In kernel/bpf/verifier.c (ffffffff81206cb2)
Location: kernel/bpf/verifier.c:10187
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
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
In kernel/bpf/verifier.c (ffffffff8123a019)
Location: kernel/bpf/verifier.c:10518
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
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
In kernel/bpf/verifier.c (ffffffff8127e174)
Location: kernel/bpf/verifier.c:11574
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
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
In kernel/bpf/verifier.c (ffffffff812d6889)
Location: kernel/bpf/verifier.c:13570
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
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
In kernel/bpf/verifier.c (ffffffff812fced2)
Location: kernel/bpf/verifier.c:15619
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
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
In kernel/bpf/verifier.c (ffffffff8131c3f2)
Location: kernel/bpf/verifier.c:16677
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:propagate_liveness
  - kernel/bpf/verifier.c:propagate_liveness
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
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026a108)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffff80001026a108-ffff80001026a17c: propagate_liveness_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049c128)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
c049c128-c049c188: propagate_liveness_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030fce0)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
c00000000030fce0-c00000000030fd78: propagate_liveness_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a4990)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffe0001a4990-ffffffe0001a49f0: propagate_liveness_reg (STB_LOCAL)
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
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811def10)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff811def10-ffffffff811def62: propagate_liveness_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d1cd0)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff811d1cd0-ffffffff811d1d22: propagate_liveness_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dcce0)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff811dcce0-ffffffff811dcd32: propagate_liveness_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int propagate_liveness_reg(struct bpf_verifier_env *env, struct bpf_reg_state *reg, struct bpf_reg_state *parent_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb0f0)
Location: kernel/bpf/verifier.c:7102
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:is_state_visited
```
**Symbols:**

```
ffffffff811eb0f0-ffffffff811eb142: propagate_liveness_reg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
