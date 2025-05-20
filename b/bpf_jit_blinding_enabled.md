# Function: <code>bpf_jit_blinding_enabled</code>

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
In kernel/bpf/core.c (ffffffff8117ec3c)
Location: include/linux/filter.h:573
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff8118aaac)
Location: include/linux/filter.h:654
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff8118f64b)
Location: include/linux/filter.h:764
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff8119dacb)
Location: include/linux/filter.h:800
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811b2303)
Location: include/linux/filter.h:849
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811c0cb3)
Location: include/linux/filter.h:917
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811d179c)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811ddd1c)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa7ec)
Location: include/linux/filter.h:1030
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
```
In kernel/bpf/verifier.c (ffffffff8120ab8f)
Location: include/linux/filter.h:1030
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9a3c)
Location: include/linux/filter.h:1039
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
```
In kernel/bpf/verifier.c (ffffffff8120cd6f)
Location: include/linux/filter.h:1039
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:fixup_bpf_calls
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa975)
Location: include/linux/filter.h:1082
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
```
In kernel/bpf/verifier.c (ffffffff8120e83f)
Location: include/linux/filter.h:1082
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c0a5)
Location: include/linux/filter.h:1106
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
```
In kernel/bpf/verifier.c (ffffffff8124305f)
Location: include/linux/filter.h:1106
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_misc_fixups
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
In kernel/bpf/core.c (ffffffff8126c53f)
Location: include/linux/filter.h:1125
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
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
In kernel/bpf/core.c (ffffffff812c157d)
Location: include/linux/filter.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
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
In kernel/bpf/core.c (ffffffff812e836e)
Location: include/linux/filter.h:1100
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
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
In kernel/bpf/core.c (ffffffff813066da)
Location: include/linux/filter.h:1130
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
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
In kernel/bpf/core.c (ffff80001025ec20)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (c0492238)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (c000000000303b98)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffe00019ce8a)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811d633c)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811c90fc)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811d410c)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
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
In kernel/bpf/core.c (ffffffff811e242c)
Location: include/linux/filter.h:986
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
</ul>

## Differences
