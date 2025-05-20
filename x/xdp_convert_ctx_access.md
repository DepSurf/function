# Function: <code>xdp_convert_ctx_access</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, int dst_reg, int src_reg, int ctx_off, struct bpf_insn *insn_buf, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179b590)
Location: net/core/filter.c:2660
Inline: False
```
**Symbols:**

```
ffffffff8179b590-ffffffff8179b5f5: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, int dst_reg, int src_reg, int ctx_off, struct bpf_insn *insn_buf, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817c94d0)
Location: net/core/filter.c:3196
Inline: False
```
**Symbols:**

```
ffffffff817c94d0-ffffffff817c9535: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e8200)
Location: net/core/filter.c:3597
Inline: False
```
**Symbols:**

```
ffffffff817e8200-ffffffff817e825b: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81863400)
Location: net/core/filter.c:4285
Inline: False
```
**Symbols:**

```
ffffffff81863400-ffffffff81863482: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818af650)
Location: net/core/filter.c:6050
Inline: False
```
**Symbols:**

```
ffffffff818af650-ffffffff818af78f: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d3a20)
Location: net/core/filter.c:6851
Inline: False
```
**Symbols:**

```
ffffffff818d3a20-ffffffff818d3b72: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81920f40)
Location: net/core/filter.c:7679
Inline: False
```
**Symbols:**

```
ffffffff81920f40-ffffffff8192109a: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81953170)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
ffffffff81953170-ffffffff819532ca: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a24460)
Location: net/core/filter.c:8026
Inline: False
```
**Symbols:**

```
ffffffff81a24460-ffffffff81a245d0: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a24840)
Location: net/core/filter.c:8846
Inline: False
```
**Symbols:**

```
ffffffff81a24840-ffffffff81a249b0: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0bc10)
Location: net/core/filter.c:8968
Inline: False
```
**Symbols:**

```
ffffffff81a0bc10-ffffffff81a0bd86: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81abdf60)
Location: net/core/filter.c:9098
Inline: False
```
**Symbols:**

```
ffffffff81abdf60-ffffffff81abe0d6: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c382a0)
Location: net/core/filter.c:9605
Inline: False
```
**Symbols:**

```
ffffffff81c382a0-ffffffff81c38455: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dec870)
Location: net/core/filter.c:9791
Inline: False
```
**Symbols:**

```
ffffffff81dec870-ffffffff81deca25: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e5e360)
Location: net/core/filter.c:9941
Inline: False
```
**Symbols:**

```
ffffffff81e5e360-ffffffff81e5e53e: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f1d750)
Location: net/core/filter.c:10032
Inline: False
```
**Symbols:**

```
ffffffff81f1d750-ffffffff81f1d92e: xdp_convert_ctx_access (STB_LOCAL)
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
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf5340)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
ffff800010bf5340-ffff800010bf54dc: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0deb8)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
c0d0deb8-c0d0e048: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cda860)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
c000000000cda860-c000000000cdaa40: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077669c)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
ffffffe00077669c-ffffffe000776814: xdp_convert_ctx_access (STB_LOCAL)
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
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f3140)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
ffffffff818f3140-ffffffff818f329a: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818acf70)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
ffffffff818acf70-ffffffff818ad0ca: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81944170)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
ffffffff81944170-ffffffff819442ca: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 xdp_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81965a60)
Location: net/core/filter.c:7766
Inline: False
```
**Symbols:**

```
ffffffff81965a60-ffffffff81965bba: xdp_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_insn *si</code>
</li>
<li>
<b>Param added. </b>
<code>u32 *target_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int dst_reg</code>
</li>
<li>
<b>Param removed. </b>
<code>int src_reg</code>
</li>
<li>
<b>Param removed. </b>
<code>int ctx_off</code>
</li>
<li>
<b>Param reordered. </b>
<code>type, dst_reg, src_reg, ctx_off, insn_buf, prog</code> ➡️ <code>type, si, insn_buf, prog, target_size</code>
</li>
</ul>
</details>
</li>
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
