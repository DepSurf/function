# Function: <code>do_jit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107a890)
Location: arch/x86/net/bpf_jit_comp.c:338
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8107a890-ffffffff8107c3dd: do_jit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107c170)
Location: arch/x86/net/bpf_jit_comp.c:350
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8107c170-ffffffff8107dd0d: do_jit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff81080710)
Location: arch/x86/net/bpf_jit_comp.c:350
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81080710-ffffffff810822ad: do_jit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107ea80)
Location: arch/x86/net/bpf_jit_comp.c:354
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8107ea80-ffffffff8108039b: do_jit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810852b0)
Location: arch/x86/net/bpf_jit_comp.c:356
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff810852b0-ffffffff81086c48: do_jit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:411
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81088660-ffffffff81089f31: do_jit.isra.3 (STB_LOCAL)
ffffffff8108a245-ffffffff8108a2b1: do_jit.isra.3.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:411
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81090130-ffffffff81091e7b: do_jit.isra.3 (STB_LOCAL)
ffffffff810921a8-ffffffff810921fb: do_jit.isra.3.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:380
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81093ed0-ffffffff81095d78: do_jit.isra.0 (STB_LOCAL)
ffffffff810960b3-ffffffff8109610a: do_jit.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:380
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8109a4a0-ffffffff8109c33a: do_jit.isra.0 (STB_LOCAL)
ffffffff8109c673-ffffffff8109c6ca: do_jit.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:655
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff810a0290-ffffffff810a2080: do_jit (STB_LOCAL)
ffffffff810a314d-ffffffff810a3211: do_jit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:792
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8109c2c0-ffffffff8109e0a3: do_jit (STB_LOCAL)
ffffffff81bdaee6-ffffffff81bdafbe: do_jit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx, bool jmp_padding);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:898
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8109cb30-ffffffff8109eeb5: do_jit (STB_LOCAL)
ffffffff81bccf79-ffffffff81bcd0a2: do_jit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, int oldproglen, struct jit_context *ctx, bool jmp_padding);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:896
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff810ad040-ffffffff810b007d: do_jit (STB_LOCAL)
ffffffff81ca3660-ffffffff81ca3801: do_jit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, u8 *rw_image, int oldproglen, struct jit_context *ctx, bool jmp_padding);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:894
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff810c2f60-ffffffff810c5db9: do_jit (STB_LOCAL)
ffffffff81e52db4-ffffffff81e52efb: do_jit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, u8 *rw_image, int oldproglen, struct jit_context *ctx, bool jmp_padding);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:966
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff810dfcb0-ffffffff810e2b58: do_jit (STB_LOCAL)
ffffffff82055962-ffffffff82055a81: do_jit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, u8 *rw_image, int oldproglen, struct jit_context *ctx, bool jmp_padding);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:966
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff810eb200-ffffffff810ee22f: do_jit (STB_LOCAL)
ffffffff820d3f46-ffffffff820d4065: do_jit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int do_jit(struct bpf_prog *bpf_prog, int *addrs, u8 *image, u8 *rw_image, int oldproglen, struct jit_context *ctx, bool jmp_padding);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:1140
Inline: False
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff810f4a50-ffffffff810f7ce4: do_jit (STB_LOCAL)
ffffffff821aee9e-ffffffff821aef39: do_jit.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:380
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81093dc0-ffffffff81095c5a: do_jit.isra.0 (STB_LOCAL)
ffffffff81095f93-ffffffff81095fea: do_jit.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:380
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81082850-ffffffff810846ea: do_jit.isra.0 (STB_LOCAL)
ffffffff81084a23-ffffffff81084a7a: do_jit.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:380
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff81093d70-ffffffff81095c0a: do_jit.isra.0 (STB_LOCAL)
ffffffff81095f43-ffffffff81095f9a: do_jit.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (0)
Location: arch/x86/net/bpf_jit_comp.c:380
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
**Symbols:**

```
ffffffff8109b970-ffffffff8109d80a: do_jit.isra.0 (STB_LOCAL)
ffffffff8109db2e-ffffffff8109db85: do_jit.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool jmp_padding</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 *rw_image</code>
</li>
<li>
<b>Param reordered. </b>
<code>bpf_prog, addrs, image, oldproglen, ctx, jmp_padding</code> ➡️ <code>bpf_prog, addrs, image, rw_image, oldproglen, ctx, jmp_padding</code>
</li>
</ul>
</details>
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
