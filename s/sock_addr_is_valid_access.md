# Function: <code>sock_addr_is_valid_access</code>

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
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818aecb0)
Location: net/core/filter.c:5422
Inline: False
```
**Symbols:**

```
ffffffff818aecb0-ffffffff818aed85: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d79d0)
Location: net/core/filter.c:6142
Inline: True
```
**Symbols:**

```
ffffffff818d79d0-ffffffff818d7aa9: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81920080)
Location: net/core/filter.c:6824
Inline: False
```
**Symbols:**

```
ffffffff81920080-ffffffff8192020f: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819522b0)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
ffffffff819522b0-ffffffff8195243f: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a234d0)
Location: net/core/filter.c:7132
Inline: False
```
**Symbols:**

```
ffffffff81a234d0-ffffffff81a2366f: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a238b0)
Location: net/core/filter.c:7938
Inline: False
```
**Symbols:**

```
ffffffff81a238b0-ffffffff81a23a4f: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0ac80)
Location: net/core/filter.c:8060
Inline: False
```
**Symbols:**

```
ffffffff81a0ac80-ffffffff81a0ae1b: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81abcfd0)
Location: net/core/filter.c:8190
Inline: False
```
**Symbols:**

```
ffffffff81abcfd0-ffffffff81abd16b: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c37c40)
Location: net/core/filter.c:8602
Inline: False
```
**Symbols:**

```
ffffffff81c37c40-ffffffff81c37e54: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81deb610)
Location: net/core/filter.c:8786
Inline: False
```
**Symbols:**

```
ffffffff81deb610-ffffffff81deb824: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e5cdf0)
Location: net/core/filter.c:8929
Inline: False
```
**Symbols:**

```
ffffffff81e5cdf0-ffffffff81e5cfdf: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f1c1e0)
Location: net/core/filter.c:9020
Inline: False
```
**Symbols:**

```
ffffffff81f1c1e0-ffffffff81f1c3cf: sock_addr_is_valid_access (STB_LOCAL)
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
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf45c0)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
ffff800010bf45c0-ffff800010bf47d4: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0cd08)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
c0d0cd08-c0d0d024: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cd9730)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
c000000000cd9730-c000000000cd98d8: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe0007759ea)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
ffffffe0007759ea-ffffffe000775b4a: sock_addr_is_valid_access (STB_LOCAL)
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
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f2280)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
ffffffff818f2280-ffffffff818f240f: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ac0b0)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
ffffffff818ac0b0-ffffffff818ac23f: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819432b0)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
ffffffff819432b0-ffffffff8194343f: sock_addr_is_valid_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool sock_addr_is_valid_access(int off, int size, enum bpf_access_type type, const struct bpf_prog *prog, struct bpf_insn_access_aux *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81964ba0)
Location: net/core/filter.c:6911
Inline: False
```
**Symbols:**

```
ffffffff81964ba0-ffffffff81964d2f: sock_addr_is_valid_access (STB_LOCAL)
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
