# Function: <code>bpf_tcp_sock_convert_ctx_access</code>

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
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8192d090)
Location: net/core/filter.c:5563
Inline: False
```
**Symbols:**

```
ffffffff8192d090-ffffffff8192d524: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195f390)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
ffffffff8195f390-ffffffff8195f824: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a32920)
Location: net/core/filter.c:5697
Inline: False
```
**Symbols:**

```
ffffffff81a32920-ffffffff81a32db4: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a34cd0)
Location: net/core/filter.c:6249
Inline: False
```
**Symbols:**

```
ffffffff81a34cd0-ffffffff81a35164: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a1be30)
Location: net/core/filter.c:6351
Inline: False
```
**Symbols:**

```
ffffffff81a1be30-ffffffff81a1c2c4: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acf5f0)
Location: net/core/filter.c:6475
Inline: False
```
**Symbols:**

```
ffffffff81acf5f0-ffffffff81acfa84: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c4cda0)
Location: net/core/filter.c:6805
Inline: False
```
**Symbols:**

```
ffffffff81c4cda0-ffffffff81c4d1b5: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e01c10)
Location: net/core/filter.c:6817
Inline: False
```
**Symbols:**

```
ffffffff81e01c10-ffffffff81e02025: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e73f20)
Location: net/core/filter.c:6974
Inline: False
```
**Symbols:**

```
ffffffff81e73f20-ffffffff81e743ba: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f336e0)
Location: net/core/filter.c:7064
Inline: False
```
**Symbols:**

```
ffffffff81f336e0-ffffffff81f33b7a: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
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
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010c02928)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
ffff800010c02928-ffff800010c02b34: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1bd74)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
c0d1bd74-c0d1c10c: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cebe40)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
c000000000cebe40-c000000000cec1f0: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000781c74)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
ffffffe000781c74-ffffffe000781ffe: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
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
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818ff360)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
ffffffff818ff360-ffffffff818ff7f4: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b9190)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
ffffffff818b9190-ffffffff818b9624: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81950390)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
ffffffff81950390-ffffffff81950824: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 bpf_tcp_sock_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81971d60)
Location: net/core/filter.c:5571
Inline: False
```
**Symbols:**

```
ffffffff81971d60-ffffffff819721f4: bpf_tcp_sock_convert_ctx_access (STB_GLOBAL)
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
