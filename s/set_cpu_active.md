# Function: <code>set_cpu_active</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void set_cpu_active(unsigned int cpu, bool active);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081fa0)
Location: kernel/cpu.c:808
Inline: False
Direct callers:
  - init/main.c:start_kernel
  - kernel/sched/core.c:sched_cpu_inactive
```
**Symbols:**

```
ffffffff81081fa0-ffffffff81081fc6: set_cpu_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81fa4601)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810b29b9)
Location: include/linux/cpumask.h:753
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81fdffb1)
Location: include/linux/cpumask.h:758
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810b8fa9)
Location: include/linux/cpumask.h:758
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff820c0db5)
Location: include/linux/cpumask.h:801
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810b3b32)
Location: include/linux/cpumask.h:801
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff826c8fb0)
Location: include/linux/cpumask.h:805
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810badd2)
Location: include/linux/cpumask.h:805
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff826f3161)
Location: include/linux/cpumask.h:807
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810c22b2)
Location: include/linux/cpumask.h:807
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff828a9f50)
Location: include/linux/cpumask.h:819
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810cb5c5)
Location: include/linux/cpumask.h:819
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff828c2744)
Location: include/linux/cpumask.h:818
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810d35d5)
Location: include/linux/cpumask.h:818
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff828cad40)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810ddb45)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff82ced15d)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810e6305)
Location: include/linux/cpumask.h:846
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff82fd97b7)
Location: include/linux/cpumask.h:852
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810e40d4)
Location: include/linux/cpumask.h:852
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff831e410b)
Location: include/linux/cpumask.h:823
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810e60ac)
Location: include/linux/cpumask.h:823
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff832c7ce8)
Location: include/linux/cpumask.h:823
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810fd2d2)
Location: include/linux/cpumask.h:823
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff8347ad0c)
Location: include/linux/cpumask.h:849
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff81119ca0)
Location: include/linux/cpumask.h:849
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff83ea584d)
Location: include/linux/cpumask.h:958
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff811415f0)
Location: include/linux/cpumask.h:958
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff836c9f0d)
Location: include/linux/cpumask.h:1010
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff8114d290)
Location: include/linux/cpumask.h:1010
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff838fabbd)
Location: include/linux/cpumask.h:1030
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff81158f50)
Location: include/linux/cpumask.h:1030
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffff800011442264)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffff80001013d3b4)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (c151c268)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (c038d478)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (c000000001365e54)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (c00000000018c14c)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffe0000047d4)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffe0000ec78a)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff828b3b33)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810d7d35)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff828abcb4)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810c6655)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff828c6a32)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810d4525)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
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
In kernel/cpu.c (ffffffff828cbd7d)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/cpu.c:boot_cpu_init
```
```
In kernel/sched/core.c (ffffffff810df935)
Location: include/linux/cpumask.h:841
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_deactivate
  - kernel/sched/core.c:sched_cpu_activate
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
