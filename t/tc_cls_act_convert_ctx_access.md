# Function: <code>tc_cls_act_convert_ctx_access</code>

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
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, int dst_reg, int src_reg, int ctx_off, struct bpf_insn *insn_buf, struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cb2d0)
Location: net/core/filter.c:3171
Inline: True
```
**Symbols:**

```
ffffffff817cb2d0-ffffffff817cb32f: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ea4d0)
Location: net/core/filter.c:3573
Inline: True
```
**Symbols:**

```
ffffffff817ea4d0-ffffffff817ea533: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865c50)
Location: net/core/filter.c:4261
Inline: True
```
**Symbols:**

```
ffffffff81865c50-ffffffff81865cb3: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3860)
Location: net/core/filter.c:6026
Inline: True
```
**Symbols:**

```
ffffffff818b3860-ffffffff818b38c3: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8a00)
Location: net/core/filter.c:6827
Inline: True
```
**Symbols:**

```
ffffffff818d8a00-ffffffff818d8a63: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81926ab0)
Location: net/core/filter.c:7655
Inline: True
```
**Symbols:**

```
ffffffff81926ab0-ffffffff81926b13: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959170)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
ffffffff81959170-ffffffff819591d3: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2b720)
Location: net/core/filter.c:8002
Inline: True
```
**Symbols:**

```
ffffffff81a2b720-ffffffff81a2b783: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2c570)
Location: net/core/filter.c:8822
Inline: True
```
**Symbols:**

```
ffffffff81a2c570-ffffffff81a2c5d3: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a13a80)
Location: net/core/filter.c:8944
Inline: True
```
**Symbols:**

```
ffffffff81a13a80-ffffffff81a13ae3: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac52e0)
Location: net/core/filter.c:9074
Inline: True
```
**Symbols:**

```
ffffffff81ac52e0-ffffffff81ac5343: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c43730)
Location: net/core/filter.c:9581
Inline: True
```
**Symbols:**

```
ffffffff81c43730-ffffffff81c437b1: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df5a80)
Location: net/core/filter.c:9767
Inline: True
```
**Symbols:**

```
ffffffff81df5a80-ffffffff81df5b01: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e67700)
Location: net/core/filter.c:9917
Inline: True
```
**Symbols:**

```
ffffffff81e67700-ffffffff81e67781: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f268c0)
Location: net/core/filter.c:10008
Inline: True
```
**Symbols:**

```
ffffffff81f268c0-ffffffff81f26941: tc_cls_act_convert_ctx_access (STB_LOCAL)
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
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfa508)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
ffff800010bfa508-ffff800010bfa5d8: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14064)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
c0d14064-c0d14104: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce28e0)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
c000000000ce28e0-c000000000ce2964: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c2f2)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
ffffffe00077c2f2-ffffffe00077c394: tc_cls_act_convert_ctx_access (STB_LOCAL)
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
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f9140)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
ffffffff818f9140-ffffffff818f91a3: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2f70)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
ffffffff818b2f70-ffffffff818b2fd3: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a170)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
ffffffff8194a170-ffffffff8194a1d3: tc_cls_act_convert_ctx_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
u32 tc_cls_act_convert_ctx_access(enum bpf_access_type type, const struct bpf_insn *si, struct bpf_insn *insn_buf, struct bpf_prog *prog, u32 *target_size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196ba80)
Location: net/core/filter.c:7742
Inline: True
```
**Symbols:**

```
ffffffff8196ba80-ffffffff8196bae3: tc_cls_act_convert_ctx_access (STB_LOCAL)
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
