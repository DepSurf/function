# Function: <code>bpf_parse_prog</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817d9b70)
Location: net/core/lwt_bpf.c:204
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff817d9b70-ffffffff817d9c2f: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817f91a0)
Location: net/core/lwt_bpf.c:204
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff817f91a0-ffffffff817f9262: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81876ab0)
Location: net/core/lwt_bpf.c:204
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81876ab0-ffffffff81876b74: bpf_parse_prog (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818c8270)
Location: net/core/lwt_bpf.c:204
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff818c8270-ffffffff818c833b: bpf_parse_prog.isra.12 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818f13e0)
Location: net/core/lwt_bpf.c:203
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff818f13e0-ffffffff818f14ab: bpf_parse_prog.isra.12 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81942d00)
Location: net/core/lwt_bpf.c:330
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81942d00-ffffffff81942dce: bpf_parse_prog.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81977cb0)
Location: net/core/lwt_bpf.c:333
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81977cb0-ffffffff81977d7e: bpf_parse_prog.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a4c8f0)
Location: net/core/lwt_bpf.c:333
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81a4c8f0-ffffffff81a4c9b7: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a52570)
Location: net/core/lwt_bpf.c:333
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81a52570-ffffffff81a52637: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a37c40)
Location: net/core/lwt_bpf.c:333
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81a37c40-ffffffff81a37d07: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aeda50)
Location: net/core/lwt_bpf.c:333
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81aeda50-ffffffff81aedb17: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c70920)
Location: net/core/lwt_bpf.c:333
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81c70920-ffffffff81c70a11: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e28940)
Location: net/core/lwt_bpf.c:333
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81e28940-ffffffff81e28a31: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9df60)
Location: net/core/lwt_bpf.c:332
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81e9df60-ffffffff81e9e051: bpf_parse_prog (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f606e0)
Location: net/core/lwt_bpf.c:332
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81f606e0-ffffffff81f607d4: bpf_parse_prog (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffff800010c1e4d8)
Location: net/core/lwt_bpf.c:333
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffff800010c1e4d8-ffff800010c1e5cc: bpf_parse_prog.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_parse_prog(struct nlattr *attr, struct bpf_lwt_prog *prog, enum bpf_prog_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d3652c)
Location: net/core/lwt_bpf.c:333
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
c0d3652c-c0d36620: bpf_parse_prog (STB_LOCAL)
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
In net/core/lwt_bpf.c (c000000000d10470)
Location: net/core/lwt_bpf.c:333
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
c000000000d10470-c000000000d105b0: bpf_parse_prog.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffe00079821a)
Location: net/core/lwt_bpf.c:333
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffe00079821a-ffffffe0007982c6: bpf_parse_prog.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81917b20)
Location: net/core/lwt_bpf.c:333
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81917b20-ffffffff81917bee: bpf_parse_prog.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818d18d0)
Location: net/core/lwt_bpf.c:333
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff818d18d0-ffffffff818d199e: bpf_parse_prog.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81968cb0)
Location: net/core/lwt_bpf.c:333
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff81968cb0-ffffffff81968d7e: bpf_parse_prog.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff8198b090)
Location: net/core/lwt_bpf.c:333
Inline: True
Direct callers:
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
  - net/core/lwt_bpf.c:bpf_build_state
```
**Symbols:**

```
ffffffff8198b090-ffffffff8198b15e: bpf_parse_prog.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
