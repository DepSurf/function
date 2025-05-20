# Function: <code>process_spin_lock</code>

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
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dcf00)
Location: kernel/bpf/verifier.c:3130
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811dcf00-ffffffff811dd073: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e96a0)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811e96a0-ffffffff811e9813: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81208ee0)
Location: kernel/bpf/verifier.c:3631
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81208ee0-ffffffff81209053: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120a3d0)
Location: kernel/bpf/verifier.c:3872
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff8120a3d0-ffffffff8120a525: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c8f0)
Location: kernel/bpf/verifier.c:4573
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff8120c8f0-ffffffff8120ca5d: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81240ab0)
Location: kernel/bpf/verifier.c:4687
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81240ab0-ffffffff81240c78: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81285f00)
Location: kernel/bpf/verifier.c:5373
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81285f00-ffffffff81286084: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5926
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff812dce70-ffffffff812dd18e: process_spin_lock (STB_LOCAL)
ffffffff82060450-ffffffff82060465: process_spin_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7010
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81306a70-ffffffff81306e05: process_spin_lock (STB_LOCAL)
ffffffff820df52a-ffffffff820df578: process_spin_lock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81324330)
Location: kernel/bpf/verifier.c:7387
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff81324330-ffffffff81324548: process_spin_lock (STB_LOCAL)
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
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026ce38)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffff80001026ce38-ffff80001026d004: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049f3f8)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
c049f3f8-c049f59c: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000313520)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
c000000000313520-c000000000313768: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a7024)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffe0001a7024-ffffffe0001a71ac: process_spin_lock (STB_LOCAL)
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
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1cc0)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811e1cc0-ffffffff811e1e33: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d4a80)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811d4a80-ffffffff811d4bf3: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dfa90)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811dfa90-ffffffff811dfc03: process_spin_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int process_spin_lock(struct bpf_verifier_env *env, int regno, bool is_lock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811edea0)
Location: kernel/bpf/verifier.c:3131
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811edea0-ffffffff811ee013: process_spin_lock (STB_LOCAL)
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
