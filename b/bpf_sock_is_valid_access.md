# Function: <code>bpf_sock_is_valid_access</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8ab5)
Location: net/core/filter.c:5941
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff818df260-ffffffff818df2a8: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192d6e0)
Location: net/core/filter.c:6607
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff8192d6e0-ffffffff8192d748: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195f9e0)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff8195f9e0-ffffffff8195fa48: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81a32f75)
Location: net/core/filter.c:6907
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_common_is_valid_access
Direct callers:
  - kernel/bpf/verifier.c:check_sock_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff81a2b7d0-ffffffff81a2b82e: bpf_sock_is_valid_access.part.0 (STB_LOCAL)
ffffffff81a32fb0-ffffffff81a3302c: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81a35335)
Location: net/core/filter.c:7713
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_common_is_valid_access
Direct callers:
  - kernel/bpf/verifier.c:check_sock_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff81a2c620-ffffffff81a2c67e: bpf_sock_is_valid_access.part.0 (STB_LOCAL)
ffffffff81a35370-ffffffff81a353ec: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81a1c495)
Location: net/core/filter.c:7835
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_common_is_valid_access
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff81a13bd0-ffffffff81a13c28: bpf_sock_is_valid_access.part.0 (STB_LOCAL)
ffffffff81a1c4d0-ffffffff81a1c542: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81acfc55)
Location: net/core/filter.c:7965
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_common_is_valid_access
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff81ac5380-ffffffff81ac53d8: bpf_sock_is_valid_access.part.0 (STB_LOCAL)
ffffffff81acfc90-ffffffff81acfd02: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81c4d395)
Location: net/core/filter.c:8360
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_common_is_valid_access
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff81c408f0-ffffffff81c409ac: bpf_sock_is_valid_access.part.0 (STB_LOCAL)
ffffffff81c4d3f0-ffffffff81c4d499: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81e02245)
Location: net/core/filter.c:8499
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_common_is_valid_access
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff81df5fd0-ffffffff81df608c: bpf_sock_is_valid_access.part.0 (STB_LOCAL)
ffffffff81e022b0-ffffffff81e02359: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81e745d5)
Location: net/core/filter.c:8651
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_common_is_valid_access
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff81e67bb0-ffffffff81e67c5e: bpf_sock_is_valid_access.part.0 (STB_LOCAL)
ffffffff81e74640-ffffffff81e74702: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff81f33d95)
Location: net/core/filter.c:8742
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sock_common_is_valid_access
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff81f26d80-ffffffff81f26e2e: bpf_sock_is_valid_access.part.0 (STB_LOCAL)
ffffffff81f33e00-ffffffff81f33ec2: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c02d68)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffff800010c02d68-ffff800010c02e2c: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1c340)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
c0d1c340-c0d1c490: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cec440)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
c000000000cec440-c000000000cec5b8: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007821da)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffe0007821da-ffffffe00078228c: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ff9b0)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff818ff9b0-ffffffff818ffa18: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b97e0)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff818b97e0-ffffffff818b9848: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819509e0)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff819509e0-ffffffff81950a48: bpf_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool bpf_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819723b0)
Location: net/core/filter.c:6694
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
  - net/core/filter.c:bpf_sock_common_is_valid_access
```
**Symbols:**

```
ffffffff819723b0-ffffffff81972418: bpf_sock_is_valid_access (STB_GLOBAL)
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
