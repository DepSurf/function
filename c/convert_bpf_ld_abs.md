# Function: <code>convert_bpf_ld_abs</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffff818b25f0)
Location: net/core/filter.c:446
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff818b25f0-ffffffff818b2840: convert_bpf_ld_abs.isra.36 (STB_LOCAL)
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
In net/core/filter.c (ffffffff818d7350)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff818d7350-ffffffff818d75d4: convert_bpf_ld_abs.isra.33 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81924e60)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81924e60-ffffffff819250e3: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81957290)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81957290-ffffffff81957513: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a22d60)
Location: net/core/filter.c:436
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81a22d60-ffffffff81a22fd7: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a230c0)
Location: net/core/filter.c:466
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81a230c0-ffffffff81a2333e: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a0a3f0)
Location: net/core/filter.c:466
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81a0a3f0-ffffffff81a0a660: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81abc900)
Location: net/core/filter.c:467
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81abc900-ffffffff81abcb70: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c373b0)
Location: net/core/filter.c:468
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81c373b0-ffffffff81c37654: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81deabf0)
Location: net/core/filter.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81deabf0-ffffffff81deae94: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e5c3f0)
Location: net/core/filter.c:470
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81e5c3f0-ffffffff81e5c691: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f1b7e0)
Location: net/core/filter.c:475
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81f1b7e0-ffffffff81f1ba81: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffff800010bf87c0)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffff800010bf87c0-ffff800010bf8a48: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool convert_bpf_ld_abs(struct sock_filter *fp, struct bpf_insn **insnp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d0c488)
Location: net/core/filter.c:447
Inline: False
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
c0d0c488-c0d0c778: convert_bpf_ld_abs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (c000000000cdf740)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
c000000000cdf740-c000000000cdfbdc: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/filter.c (ffffffe00077a702)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffe00077a702-ffffffe00077a9ae: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
```
</details>
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
In net/core/filter.c (ffffffff818f7260)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff818f7260-ffffffff818f74e3: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff818b1090)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff818b1090-ffffffff818b1313: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81948290)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81948290-ffffffff81948513: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
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
In net/core/filter.c (ffffffff81969ba0)
Location: net/core/filter.c:447
Inline: True
Direct callers:
  - net/core/filter.c:bpf_convert_filter
  - net/core/filter.c:bpf_convert_filter
```
**Symbols:**

```
ffffffff81969ba0-ffffffff81969e23: convert_bpf_ld_abs.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
