# Function: <code>check_helper_mem_access</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811956a0)
Location: kernel/bpf/verifier.c:1070
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811956a0-ffffffff811956f5: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a1f50)
Location: kernel/bpf/verifier.c:1366
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811a1f50-ffffffff811a1fa9: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ba6d0)
Location: kernel/bpf/verifier.c:1916
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811ba6d0-ffffffff811ba9b6: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ca220)
Location: kernel/bpf/verifier.c:2178
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811ca220-ffffffff811ca512: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dd170)
Location: kernel/bpf/verifier.c:3087
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811dd170-ffffffff811dd629: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e9910)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811e9910-ffffffff811e9dee: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120c920)
Location: kernel/bpf/verifier.c:3584
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff8120c920-ffffffff8120ca15: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff8120f360)
Location: kernel/bpf/verifier.c:3803
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff8120f360-ffffffff8120f526: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81210cc0)
Location: kernel/bpf/verifier.c:4476
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
```
**Symbols:**

```
ffffffff81210cc0-ffffffff81210eae: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:4590
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
```
**Symbols:**

```
ffffffff812457e0-ffffffff81245a76: check_helper_mem_access (STB_LOCAL)
ffffffff81cb89b7-ffffffff81cb89e9: check_helper_mem_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5168
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
```
**Symbols:**

```
ffffffff8127e7f0-ffffffff8127eb81: check_helper_mem_access (STB_LOCAL)
ffffffff81e68fd4-ffffffff81e69081: check_helper_mem_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:5699
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
```
**Symbols:**

```
ffffffff812e8310-ffffffff812e871a: check_helper_mem_access (STB_LOCAL)
ffffffff82060eb9-ffffffff82060f61: check_helper_mem_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:6780
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
```
**Symbols:**

```
ffffffff813136c0-ffffffff81313b0c: check_helper_mem_access (STB_LOCAL)
ffffffff820e02da-ffffffff820e037c: check_helper_mem_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/verifier.c (0)
Location: kernel/bpf/verifier.c:7153
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_reg
  - kernel/bpf/verifier.c:check_mem_size_reg
```
**Symbols:**

```
ffffffff81333a70-ffffffff81333ec0: check_helper_mem_access (STB_LOCAL)
ffffffff821bc619-ffffffff821bc6bb: check_helper_mem_access.cold (STB_LOCAL)
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
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026d118)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffff80001026d118-ffff80001026d590: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049f6b8)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
c049f6b8-c049fbb4: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c0000000003138d0)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
c0000000003138d0-c000000000313ea8: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a726e)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffe0001a726e-ffffffe0001a762c: check_helper_mem_access (STB_LOCAL)
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
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e1f30)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811e1f30-ffffffff811e240e: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d4cf0)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811d4cf0-ffffffff811d51ce: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811dfd00)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811dfd00-ffffffff811e01de: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int check_helper_mem_access(struct bpf_verifier_env *env, int regno, int access_size, bool zero_size_allowed, struct bpf_call_arg_meta *meta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ee110)
Location: kernel/bpf/verifier.c:3088
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
  - kernel/bpf/verifier.c:check_func_arg
```
**Symbols:**

```
ffffffff811ee110-ffffffff811ee5ee: check_helper_mem_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
