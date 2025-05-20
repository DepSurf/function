# Function: <code>bpf_fill_lwt_prog</code>

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
int bpf_fill_lwt_prog(struct sk_buff *skb, int attr, struct bpf_lwt_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff817da1e0)
Location: net/core/lwt_bpf.c:312
Inline: False
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff817da1e0-ffffffff817da271: bpf_fill_lwt_prog (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff817f948c)
Location: net/core/lwt_bpf.c:314
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff817f93f0-ffffffff817f9475: bpf_fill_lwt_prog.part.8 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81876d9c)
Location: net/core/lwt_bpf.c:314
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81876d00-ffffffff81876d85: bpf_fill_lwt_prog.part.9 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818c81f5)
Location: net/core/lwt_bpf.c:314
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff818c8160-ffffffff818c81ea: bpf_fill_lwt_prog.isra.9.part.10 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818f1365)
Location: net/core/lwt_bpf.c:313
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff818f12d0-ffffffff818f1357: bpf_fill_lwt_prog.isra.9.part.10 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81943005)
Location: net/core/lwt_bpf.c:441
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81942f70-ffffffff81942ff7: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81977fb5)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81977f20-ffffffff81977fa7: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a4c725)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81a4c690-ffffffff81a4c717: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a523a5)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81a52310-ffffffff81a52397: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a37b85)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81a37af0-ffffffff81a37b77: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aed9d5)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81aed940-ffffffff81aed9c7: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c708a5)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81c70800-ffffffff81c7089f: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e288b5)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81e28800-ffffffff81e2889f: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9ded5)
Location: net/core/lwt_bpf.c:443
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81e9de20-ffffffff81e9debf: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f60655)
Location: net/core/lwt_bpf.c:443
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81f605a0-ffffffff81f6063f: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffff800010c1e86c)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffff800010c1e790-ffff800010c1e850: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/lwt_bpf.c (c0d36888)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
c0d367e8-c0d36874: bpf_fill_lwt_prog.part.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (c000000000d10944)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
c000000000d10810-c000000000d10918: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffe0007984de)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffe000798426-ffffffe0007984c4: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81917e25)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81917d90-ffffffff81917e17: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff818d1bd5)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff818d1b40-ffffffff818d1bc7: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff81968fb5)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff81968f20-ffffffff81968fa7: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
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
In net/core/lwt_bpf.c (ffffffff8198b395)
Location: net/core/lwt_bpf.c:444
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
Direct callers:
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
  - net/core/lwt_bpf.c:bpf_fill_encap_info
```
**Symbols:**

```
ffffffff8198b300-ffffffff8198b387: bpf_fill_lwt_prog.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
