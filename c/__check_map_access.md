# Function: <code>__check_map_access</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811a1680)
Location: kernel/bpf/verifier.c:801
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811a1680-ffffffff811a16d0: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811b9720)
Location: kernel/bpf/verifier.c:1237
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811b9720-ffffffff811b977a: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811c7c50)
Location: kernel/bpf/verifier.c:1419
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811c7c50-ffffffff811c7cae: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811db370)
Location: kernel/bpf/verifier.c:2151
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811db370-ffffffff811db3d1: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e7ac0)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811e7ac0-ffffffff811e7b21: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffff80001026b4e8)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffff80001026b4e8-ffff80001026b598: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c049d560)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
c049d560-c049d5f4: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (c000000000311500)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
c000000000311500-c0000000003115a0: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffe0001a5ace)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffe0001a5ace-ffffffe0001a5b5a: __check_map_access (STB_LOCAL)
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
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811e00e0)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811e00e0-ffffffff811e0141: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811d2ea0)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811d2ea0-ffffffff811d2f01: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ddeb0)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811ddeb0-ffffffff811ddf11: __check_map_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __check_map_access(struct bpf_verifier_env *env, u32 regno, int off, int size, bool zero_size_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff811ec2c0)
Location: kernel/bpf/verifier.c:2152
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_map_access
  - kernel/bpf/verifier.c:check_map_access
```
**Symbols:**

```
ffffffff811ec2c0-ffffffff811ec321: __check_map_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
