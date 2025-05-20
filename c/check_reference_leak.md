# Function: <code>check_reference_leak</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ca520)
Location: kernel/bpf/verifier.c:2834
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811ca520-ffffffff811ca592: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dd630)
Location: kernel/bpf/verifier.c:3926
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811dd630-ffffffff811dd69e: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9df0)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e9df0-ffffffff811e9e5e: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81209b50)
Location: kernel/bpf/verifier.c:4584
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81209b50-ffffffff81209bbe: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120b2b0)
Location: kernel/bpf/verifier.c:5036
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff8120b2b0-ffffffff8120b31e: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120d150)
Location: kernel/bpf/verifier.c:5889
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_abs
```
**Symbols:**

```
ffffffff8120d150-ffffffff8120d1be: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81241370)
Location: kernel/bpf/verifier.c:6141
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff81241370-ffffffff812413f7: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff812868d0)
Location: kernel/bpf/verifier.c:7040
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812868d0-ffffffff81286963: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7799
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812dda80-ffffffff812ddb6f: check_reference_leak (STB_LOCAL)
ffffffff82060499-ffffffff820604c3: check_reference_leak.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9235
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_abs
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff812f8b40-ffffffff812f8c37: check_reference_leak (STB_LOCAL)
ffffffff820dea62-ffffffff820dea93: check_reference_leak.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env, bool exception_exit);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:9943
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_ld_abs
```
**Symbols:**

```
ffffffff81317eb0-ffffffff81317fcc: check_reference_leak (STB_LOCAL)
ffffffff821baac0-ffffffff821baaf7: check_reference_leak.cold (STB_LOCAL)
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
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026d590)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffff80001026d590-ffff80001026d61c: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049fbb4)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c049fbb4-c049fc28: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000313eb0)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
c000000000313eb0-c000000000313f74: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a762c)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffe0001a762c-ffffffe0001a76a4: check_reference_leak (STB_LOCAL)
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
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e2410)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e2410-ffffffff811e247e: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d51d0)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811d51d0-ffffffff811d523e: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e01e0)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811e01e0-ffffffff811e024e: check_reference_leak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_reference_leak(struct bpf_verifier_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ee5f0)
Location: kernel/bpf/verifier.c:3929
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:do_check
  - kernel/bpf/verifier.c:check_helper_call
```
**Symbols:**

```
ffffffff811ee5f0-ffffffff811ee65e: check_reference_leak (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool exception_exit</code>
</li>
</ul>
</details>
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
