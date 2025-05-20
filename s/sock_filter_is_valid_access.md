# Function: <code>sock_filter_is_valid_access</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, enum bpf_reg_type *reg_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ca720)
Location: net/core/filter.c:2845
Inline: True
```
**Symbols:**

```
ffffffff817ca720-ffffffff817ca75d: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9960)
Location: net/core/filter.c:3180
Inline: True
```
**Symbols:**

```
ffffffff817e9960-ffffffff817e999d: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81864f20)
Location: net/core/filter.c:3677
Inline: True
```
**Symbols:**

```
ffffffff81864f20-ffffffff81864f6e: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818aeaf0)
Location: net/core/filter.c:5238
Inline: False
```
**Symbols:**

```
ffffffff818aeaf0-ffffffff818aeb7f: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8ab0)
Location: net/core/filter.c:5953
Inline: True
```
**Symbols:**

```
ffffffff818d8ab0-ffffffff818d8b43: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192d770)
Location: net/core/filter.c:6635
Inline: True
```
**Symbols:**

```
ffffffff8192d770-ffffffff8192d809: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195fa70)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
ffffffff8195fa70-ffffffff8195fb09: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2cff0)
Location: net/core/filter.c:6936
Inline: True
```
**Symbols:**

```
ffffffff81a2cff0-ffffffff81a2d099: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e5a0)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
ffffffff81a2e5a0-ffffffff81a2e64c: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a15b30)
Location: net/core/filter.c:7864
Inline: True
```
**Symbols:**

```
ffffffff81a15b30-ffffffff81a15bd1: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac6da0)
Location: net/core/filter.c:7994
Inline: True
```
**Symbols:**

```
ffffffff81ac6da0-ffffffff81ac6e41: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c42510)
Location: net/core/filter.c:8397
Inline: True
```
**Symbols:**

```
ffffffff81c42510-ffffffff81c425dc: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df7ab0)
Location: net/core/filter.c:8536
Inline: True
```
**Symbols:**

```
ffffffff81df7ab0-ffffffff81df7b7c: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e69290)
Location: net/core/filter.c:8688
Inline: True
```
**Symbols:**

```
ffffffff81e69290-ffffffff81e6936e: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f28870)
Location: net/core/filter.c:8779
Inline: True
```
**Symbols:**

```
ffffffff81f28870-ffffffff81f2894e: sock_filter_is_valid_access (STB_LOCAL)
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c02ea0)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
ffff800010c02ea0-ffff800010c02fc0: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1c4c0)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
c0d1c4c0-c0d1c60c: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cec600)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
c000000000cec600-c000000000cec7e0: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007822ea)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
ffffffe0007822ea-ffffffe000782382: sock_filter_is_valid_access (STB_LOCAL)
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
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ffa40)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
ffffffff818ffa40-ffffffff818ffad9: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b9870)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
ffffffff818b9870-ffffffff818b9909: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81950a70)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
ffffffff81950a70-ffffffff81950b09: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool sock_filter_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81972440)
Location: net/core/filter.c:6722
Inline: True
```
**Symbols:**

```
ffffffff81972440-ffffffff819724d9: sock_filter_is_valid_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_insn_access_aux *info</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_reg_type *reg_type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_prog *prog</code>
</li>
<li>
<b>Param reordered. </b>
<code>off, size, type, info</code> ➡️ <code>off, size, type, prog, info</code>
</li>
</ul>
</details>
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
