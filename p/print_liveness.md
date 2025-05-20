# Function: <code>print_liveness</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b8080)
Location: kernel/bpf/verifier.c:266
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811b8080-ffffffff811b80de: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7340)
Location: kernel/bpf/verifier.c:397
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811c7340-ffffffff811c73b7: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811da520)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811da520-ffffffff811da597: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e6950)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811e6950-ffffffff811e69c7: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812072e0)
Location: kernel/bpf/verifier.c:515
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff812072e0-ffffffff81207357: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812070c0)
Location: kernel/bpf/verifier.c:540
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff812070c0-ffffffff81207137: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81206110)
Location: kernel/bpf/verifier.c:588
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff81206110-ffffffff81206187: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81239020)
Location: kernel/bpf/verifier.c:589
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff81239020-ffffffff81239097: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8127f180)
Location: kernel/bpf/verifier.c:591
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff8127f180-ffffffff8127f207: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812d47c0)
Location: kernel/bpf/verifier.c:628
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff812d47c0-ffffffff812d4847: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812fa6f0)
Location: kernel/bpf/verifier.c:653
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff812fa6f0-ffffffff812fa767: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/log.c (ffffffff813451d0)
Location: kernel/bpf/log.c:499
Inline: True
Direct callers:
  - kernel/bpf/log.c:print_verifier_state
  - kernel/bpf/log.c:print_verifier_state
  - kernel/bpf/log.c:print_verifier_state
  - kernel/bpf/log.c:print_verifier_state
  - kernel/bpf/log.c:print_verifier_state
```
**Symbols:**

```
ffffffff813451d0-ffffffff81345247: print_liveness (STB_LOCAL)
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
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026a568)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffff80001026a568-ffff80001026a604: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049c188)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
c049c188-c049c218: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c00000000030fd80)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
c00000000030fd80-c00000000030fe5c: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a4d3c)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffe0001a4d3c-ffffffe0001a4ddc: print_liveness (STB_LOCAL)
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
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811def70)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811def70-ffffffff811defe7: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d1d30)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811d1d30-ffffffff811d1da7: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dcd40)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811dcd40-ffffffff811dcdb7: print_liveness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void print_liveness(struct bpf_verifier_env *env, enum bpf_reg_liveness live);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811eb150)
Location: kernel/bpf/verifier.c:412
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:print_verifier_state
  - kernel/bpf/verifier.c:print_verifier_state
```
**Symbols:**

```
ffffffff811eb150-ffffffff811eb1c7: print_liveness (STB_LOCAL)
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
