# Function: <code>bpf_lwt_prog_cmp</code>

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
int bpf_lwt_prog_cmp(struct bpf_lwt_prog *a, struct bpf_lwt_prog *b);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817da2e0)
Location: net/core/lwt_bpf.c:355
Inline: False
```
**Symbols:**

```
ffffffff817da2e0-ffffffff817da313: bpf_lwt_prog_cmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817f8db0)
Location: net/core/lwt_bpf.c:357
Inline: True
```
**Symbols:**

```
ffffffff817f8db0-ffffffff817f8ddd: bpf_lwt_prog_cmp.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81876690)
Location: net/core/lwt_bpf.c:357
Inline: True
```
**Symbols:**

```
ffffffff81876690-ffffffff818766bd: bpf_lwt_prog_cmp.isra.7 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818c7db0)
Location: net/core/lwt_bpf.c:357
Inline: True
```
**Symbols:**

```
ffffffff818c7db0-ffffffff818c7ddc: bpf_lwt_prog_cmp.isra.7 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818f0f10)
Location: net/core/lwt_bpf.c:356
Inline: True
```
**Symbols:**

```
ffffffff818f0f10-ffffffff818f0f3c: bpf_lwt_prog_cmp.isra.7 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff819428e0)
Location: net/core/lwt_bpf.c:484
Inline: True
```
**Symbols:**

```
ffffffff819428e0-ffffffff8194290c: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81977830)
Location: net/core/lwt_bpf.c:487
Inline: True
```
**Symbols:**

```
ffffffff81977830-ffffffff8197785c: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a4d3d3)
Location: net/core/lwt_bpf.c:487
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a53093)
Location: net/core/lwt_bpf.c:487
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a388c3)
Location: net/core/lwt_bpf.c:487
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aee7a3)
Location: net/core/lwt_bpf.c:487
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c716f3)
Location: net/core/lwt_bpf.c:487
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_encap_cmp
  - net/core/lwt_bpf.c:bpf_encap_cmp
  - net/core/lwt_bpf.c:bpf_encap_cmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e297d3)
Location: net/core/lwt_bpf.c:487
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_encap_cmp
  - net/core/lwt_bpf.c:bpf_encap_cmp
  - net/core/lwt_bpf.c:bpf_encap_cmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9ee13)
Location: net/core/lwt_bpf.c:486
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_encap_cmp
  - net/core/lwt_bpf.c:bpf_encap_cmp
  - net/core/lwt_bpf.c:bpf_encap_cmp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f61583)
Location: net/core/lwt_bpf.c:486
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_encap_cmp
  - net/core/lwt_bpf.c:bpf_encap_cmp
  - net/core/lwt_bpf.c:bpf_encap_cmp
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
In net/core/lwt_bpf.c (ffff800010c1e400)
Location: net/core/lwt_bpf.c:487
Inline: True
```
**Symbols:**

```
ffff800010c1e400-ffff800010c1e454: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_lwt_prog_cmp(struct bpf_lwt_prog *a, struct bpf_lwt_prog *b);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d35ef8)
Location: net/core/lwt_bpf.c:487
Inline: False
```
**Symbols:**

```
c0d35ef8-c0d35f40: bpf_lwt_prog_cmp (STB_LOCAL)
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
In net/core/lwt_bpf.c (c000000000d10200)
Location: net/core/lwt_bpf.c:487
Inline: True
```
**Symbols:**

```
c000000000d10200-c000000000d103b8: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffe000798154)
Location: net/core/lwt_bpf.c:487
Inline: True
```
**Symbols:**

```
ffffffe000798154-ffffffe00079819e: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff819176a0)
Location: net/core/lwt_bpf.c:487
Inline: True
```
**Symbols:**

```
ffffffff819176a0-ffffffff819176cc: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818d1450)
Location: net/core/lwt_bpf.c:487
Inline: True
```
**Symbols:**

```
ffffffff818d1450-ffffffff818d147c: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81968830)
Location: net/core/lwt_bpf.c:487
Inline: True
```
**Symbols:**

```
ffffffff81968830-ffffffff8196885c: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff8198abe0)
Location: net/core/lwt_bpf.c:487
Inline: True
```
**Symbols:**

```
ffffffff8198abe0-ffffffff8198ac0c: bpf_lwt_prog_cmp.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
