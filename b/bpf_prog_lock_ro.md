# Function: <code>bpf_prog_lock_ro</code>

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
In kernel/bpf/core.c (ffffffff811714ca)
Location: include/linux/filter.h:405
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
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
In kernel/bpf/core.c (ffffffff8117f2bc)
Location: include/linux/filter.h:468
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
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
In kernel/bpf/core.c (ffffffff8118b12c)
Location: include/linux/filter.h:549
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
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
In kernel/bpf/core.c (ffffffff8118fc71)
Location: include/linux/filter.h:614
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
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
In kernel/bpf/core.c (ffffffff8119e3f7)
Location: include/linux/filter.h:619
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2c2e)
Location: include/linux/filter.h:676
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811bfd6e)
Location: include/linux/filter.h:676
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c17a9)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811d1077)
Location: include/linux/filter.h:697
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1ead)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811dfea9)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de44d)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811ec669)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:802
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:802
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:811
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:811
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:854
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:854
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:875
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:875
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:878
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:878
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:850
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:850
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:850
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:850
Inline: True
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
In kernel/bpf/core.c (0)
Location: include/linux/filter.h:884
Inline: True
```
```
In kernel/bpf/verifier.c (0)
Location: include/linux/filter.h:884
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f6ec)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffff80001026ff04)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0492ac8)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (c04a2218)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
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
In kernel/bpf/core.c (c0000000003046f8)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (c000000000316e14)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d59a)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffe0001a9716)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6a6d)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811e4c89)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c982d)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811d7a49)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d483d)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811e2a59)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2b6d)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_select_runtime
```
```
In kernel/bpf/verifier.c (ffffffff811f0e36)
Location: include/linux/filter.h:771
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:jit_subprogs
```
</details>
</li>
</ul>

## Differences
