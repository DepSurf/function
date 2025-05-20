# Function: <code>bpf_prog_unlock_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107c674)
Location: include/linux/filter.h:434
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff8107e004)
Location: include/linux/filter.h:501
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810825a4)
Location: include/linux/filter.h:582
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
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
In kernel/bpf/core.c (ffffffff8118f547)
Location: include/linux/filter.h:681
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
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
In kernel/bpf/core.c (ffffffff8119d9b7)
Location: include/linux/filter.h:686
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2157)
Location: include/linux/filter.h:723
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0a97)
Location: include/linux/filter.h:751
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d15d4)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ddb54)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
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
In kernel/bpf/core.c (ffffffff811faf7a)
Location: include/linux/filter.h:852
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
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
In kernel/bpf/core.c (ffffffff811f98d8)
Location: include/linux/filter.h:861
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
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
In kernel/bpf/core.c (ffffffff811fa7ff)
Location: include/linux/filter.h:903
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
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
In kernel/bpf/core.c (ffffffff8122bf1b)
Location: include/linux/filter.h:924
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810c6f23)
Location: include/linux/filter.h:918
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
```
In kernel/bpf/core.c (ffffffff8126da92)
Location: include/linux/filter.h:918
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e3f73)
Location: include/linux/filter.h:889
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
```
In kernel/bpf/core.c (ffffffff812c2ed1)
Location: include/linux/filter.h:889
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ef5c3)
Location: include/linux/filter.h:888
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
```
In kernel/bpf/core.c (ffffffff812e9dc4)
Location: include/linux/filter.h:888
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f88a3)
Location: include/linux/filter.h:922
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
```
In kernel/bpf/core.c (ffffffff81308e4e)
Location: include/linux/filter.h:922
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025e9c0)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0492004)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/net/bpf_jit_comp64.c (c000000000109130)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_free
```
```
In kernel/bpf/core.c (c000000000303888)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019cc8a)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6174)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c8f34)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3f44)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2264)
Location: include/linux/filter.h:817
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
</ul>

## Differences
