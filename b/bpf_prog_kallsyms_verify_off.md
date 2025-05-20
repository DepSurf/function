# Function: <code>bpf_prog_kallsyms_verify_off</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118f588)
Location: kernel/bpf/core.c:387
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
In kernel/bpf/core.c (ffffffff8119d9f8)
Location: kernel/bpf/core.c:396
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
In kernel/bpf/core.c (ffffffff811b2194)
Location: kernel/bpf/core.c:475
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
In kernel/bpf/core.c (ffffffff811c0ad4)
Location: kernel/bpf/core.c:598
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
In kernel/bpf/core.c (ffffffff811d15f5)
Location: kernel/bpf/core.c:640
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
In kernel/bpf/core.c (ffffffff811ddb75)
Location: kernel/bpf/core.c:640
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
In kernel/bpf/core.c (ffffffff811fa6dc)
Location: kernel/bpf/core.c:640
Inline: True
Inline callers:
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
In kernel/bpf/core.c (ffffffff811f97bc)
Location: kernel/bpf/core.c:636
Inline: True
Inline callers:
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
In kernel/bpf/core.c (ffffffff811fa65f)
Location: kernel/bpf/core.c:642
Inline: True
Inline callers:
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
In kernel/bpf/core.c (ffffffff8122bd6f)
Location: kernel/bpf/core.c:643
Inline: True
Inline callers:
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810c6ef7)
Location: include/linux/filter.h:1067
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
```
In kernel/bpf/core.c (ffffffff8126d8e9)
Location: include/linux/filter.h:1067
Inline: True
Inline callers:
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810e3f47)
Location: include/linux/filter.h:1042
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
```
In kernel/bpf/core.c (ffffffff812c2d09)
Location: include/linux/filter.h:1042
Inline: True
Inline callers:
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810ef597)
Location: include/linux/filter.h:1042
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
```
In kernel/bpf/core.c (ffffffff812e9bf9)
Location: include/linux/filter.h:1042
Inline: True
Inline callers:
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
In arch/x86/net/bpf_jit_comp.c (ffffffff810f8877)
Location: include/linux/filter.h:1072
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
```
```
In kernel/bpf/core.c (ffffffff81308149)
Location: include/linux/filter.h:1072
Inline: True
Inline callers:
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
In kernel/bpf/core.c (ffff80001025ea1c)
Location: kernel/bpf/core.c:640
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
In kernel/bpf/core.c (c0492020)
Location: kernel/bpf/core.c:640
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003038e0)
Location: kernel/bpf/core.c:640
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
In kernel/bpf/core.c (ffffffe00019ccca)
Location: kernel/bpf/core.c:640
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
In kernel/bpf/core.c (ffffffff811d6195)
Location: kernel/bpf/core.c:640
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
In kernel/bpf/core.c (ffffffff811c8f55)
Location: kernel/bpf/core.c:640
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
In kernel/bpf/core.c (ffffffff811d3f65)
Location: kernel/bpf/core.c:640
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
In kernel/bpf/core.c (ffffffff811e2285)
Location: kernel/bpf/core.c:640
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_free
```
</details>
</li>
</ul>

## Differences
