# Function: <code>memblock_alloc_from</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup_percpu.c (ffffffff828b335d)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff828b67b4)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff82cdb854)
Location: include/linux/memblock.h:388
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
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
In arch/x86/kernel/setup_percpu.c (ffffffff82fc7caa)
Location: include/linux/memblock.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
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
In arch/x86/kernel/setup_percpu.c (ffffffff831d260b)
Location: include/linux/memblock.h:421
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
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
In arch/x86/kernel/setup_percpu.c (ffffffff832b4e7d)
Location: include/linux/memblock.h:422
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_alloc_bootmem
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
In mm/percpu.c (ffffffff8348a98e)
Location: include/linux/memblock.h:438
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
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
In mm/percpu.c (ffffffff83ebb8d1)
Location: include/linux/memblock.h:438
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
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
In mm/percpu.c (ffffffff836e3f01)
Location: include/linux/memblock.h:437
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
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
In mm/percpu.c (ffffffff83916791)
Location: include/linux/memblock.h:449
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_fc_alloc
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c152e57c)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dfl_fc_alloc
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe000012b5e)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dfl_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff828a47bb)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff8289c8fd)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff828b76cb)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
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
In arch/x86/kernel/setup_percpu.c (ffffffff828b77cc)
Location: include/linux/memblock.h:382
Inline: True
Inline callers:
  - arch/x86/kernel/setup_percpu.c:pcpu_fc_alloc
```
</details>
</li>
</ul>

## Differences
