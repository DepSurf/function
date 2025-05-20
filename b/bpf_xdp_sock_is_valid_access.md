# Function: <code>bpf_xdp_sock_is_valid_access</code>

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
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192d530)
Location: net/core/filter.c:5739
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8192d530-ffffffff8192d556: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195f830)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff8195f830-ffffffff8195f856: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a32dc0)
Location: net/core/filter.c:5877
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_sock_access
```
**Symbols:**

```
ffffffff81a32dc0-ffffffff81a32de6: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a35170)
Location: net/core/filter.c:6429
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_sock_access
```
**Symbols:**

```
ffffffff81a35170-ffffffff81a35196: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1c2d0)
Location: net/core/filter.c:6531
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81a1c2d0-ffffffff81a1c2f6: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acfa90)
Location: net/core/filter.c:6655
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81acfa90-ffffffff81acfab6: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4d1c0)
Location: net/core/filter.c:6985
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81c4d1c0-ffffffff81c4d1ef: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e02040)
Location: net/core/filter.c:6997
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81e02040-ffffffff81e0206f: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e743d0)
Location: net/core/filter.c:7153
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81e743d0-ffffffff81e743ff: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f33b90)
Location: net/core/filter.c:7243
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81f33b90-ffffffff81f33bbf: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
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
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c02b38)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffff800010c02b38-ffff800010c02b84: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1c10c)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c0d1c10c-c0d1c150: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cec1f0)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
c000000000cec1f0-c000000000cec238: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000781ffe)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffe000781ffe-ffffffe00078203a: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
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
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ff800)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff818ff800-ffffffff818ff826: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b9630)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff818b9630-ffffffff818b9656: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81950830)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81950830-ffffffff81950856: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bpf_xdp_sock_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81972200)
Location: net/core/filter.c:5747
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:check_mem_access
```
**Symbols:**

```
ffffffff81972200-ffffffff81972226: bpf_xdp_sock_is_valid_access (STB_GLOBAL)
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
