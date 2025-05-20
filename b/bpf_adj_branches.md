# Function: <code>bpf_adj_branches</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117eab7)
Location: kernel/bpf/core.c:149
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118a927)
Location: kernel/bpf/core.c:231
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118f057)
Location: kernel/bpf/core.c:234
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d4c7)
Location: kernel/bpf/core.c:230
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, u32 delta, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b0380)
Location: kernel/bpf/core.c:256
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811b0380-ffffffff811b04e3: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, u32 delta, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811be9a0)
Location: kernel/bpf/core.c:344
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811be9a0-ffffffff811beb03: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ce540)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811ce540-ffffffff811ce6ba: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dab60)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811dab60-ffffffff811dacda: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7600)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811f7600-ffffffff811f7787: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f6160)
Location: kernel/bpf/core.c:368
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811f6160-ffffffff811f62e7: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7050)
Location: kernel/bpf/core.c:374
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811f7050-ffffffff811f71de: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81228620)
Location: kernel/bpf/core.c:374
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff81228620-ffffffff812287ae: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126bea0)
Location: kernel/bpf/core.c:379
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff8126bea0-ffffffff8126c085: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c1090)
Location: kernel/bpf/core.c:387
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff812c1090-ffffffff812c1275: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e7e40)
Location: kernel/bpf/core.c:388
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff812e7e40-ffffffff812e8025: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81306180)
Location: kernel/bpf/core.c:405
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff81306180-ffffffff813063d5: bpf_adj_branches (STB_LOCAL)
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
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025b670)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffff80001025b670-ffff80001025b80c: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c048e7cc)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
c048e7cc-c048ea1c: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000002ff010)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
c0000000002ff010-c0000000002ff210: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019a3cc)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffe00019a3cc-ffffffe00019a512: bpf_adj_branches (STB_LOCAL)
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
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3180)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811d3180-ffffffff811d32fa: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c5f40)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811c5f40-ffffffff811c60ba: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d0f50)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811d0f50-ffffffff811d10ca: bpf_adj_branches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_adj_branches(struct bpf_prog *prog, u32 pos, s32 end_old, s32 end_new, const bool probe_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811df240)
Location: kernel/bpf/core.c:372
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_remove_insns
  - kernel/bpf/core.c:bpf_patch_insn_single
  - kernel/bpf/core.c:bpf_patch_insn_single
```
**Symbols:**

```
ffffffff811df240-ffffffff811df3ba: bpf_adj_branches (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>s32 end_old</code>
</li>
<li>
<b>Param added. </b>
<code>s32 end_new</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 delta</code>
</li>
<li>
<b>Param reordered. </b>
<code>prog, pos, delta, probe_pass</code> ➡️ <code>prog, pos, end_old, end_new, probe_pass</code>
</li>
</ul>
</details>
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
