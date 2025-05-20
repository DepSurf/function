# Function: <code>sk_skb_convert_ctx_access</code>

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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818636b0)
Location: net/core/filter.c:4446
Inline: False
```
**Symbols:**

```
ffffffff818636b0-ffffffff818636e7: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b38d0)
Location: net/core/filter.c:6598
Inline: True
```
**Symbols:**

```
ffffffff818b38d0-ffffffff818b3907: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8a70)
Location: net/core/filter.c:7399
Inline: True
```
**Symbols:**

```
ffffffff818d8a70-ffffffff818d8aa7: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81926b20)
Location: net/core/filter.c:8220
Inline: True
```
**Symbols:**

```
ffffffff81926b20-ffffffff81926b57: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819591e0)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
ffffffff819591e0-ffffffff81959217: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2b790)
Location: net/core/filter.c:8621
Inline: True
```
**Symbols:**

```
ffffffff81a2b790-ffffffff81a2b7c7: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2c5e0)
Location: net/core/filter.c:9489
Inline: True
```
**Symbols:**

```
ffffffff81a2c5e0-ffffffff81a2c617: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a13af0)
Location: net/core/filter.c:9635
Inline: True
```
**Symbols:**

```
ffffffff81a13af0-ffffffff81a13bcf: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac0be0)
Location: net/core/filter.c:9789
Inline: False
```
**Symbols:**

```
ffffffff81ac0be0-ffffffff81ac0e3d: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c437c0)
Location: net/core/filter.c:10296
Inline: False
```
**Symbols:**

```
ffffffff81c437c0-ffffffff81c43a59: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81def790)
Location: net/core/filter.c:10501
Inline: False
```
**Symbols:**

```
ffffffff81def790-ffffffff81defa29: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e613d0)
Location: net/core/filter.c:10651
Inline: False
```
**Symbols:**

```
ffffffff81e613d0-ffffffff81e6166f: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f207c0)
Location: net/core/filter.c:10742
Inline: False
```
**Symbols:**

```
ffffffff81f207c0-ffffffff81f20a5f: sk_skb_convert_ctx_access (STB_LOCAL)
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfa5d8)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
ffff800010bfa5d8-ffff800010bfa670: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14104)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
c0d14104-c0d14170: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce2970)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
c000000000ce2970-c000000000ce29c4: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c394)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
ffffffe00077c394-ffffffe00077c408: sk_skb_convert_ctx_access (STB_LOCAL)
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
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f91b0)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
ffffffff818f91b0-ffffffff818f91e7: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2fe0)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
ffffffff818b2fe0-ffffffff818b3017: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a1e0)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
ffffffff8194a1e0-ffffffff8194a217: sk_skb_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 sk_skb_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196baf0)
Location: net/core/filter.c:8307
Inline: True
```
**Symbols:**

```
ffffffff8196baf0-ffffffff8196bb27: sk_skb_convert_ctx_access (STB_LOCAL)
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
