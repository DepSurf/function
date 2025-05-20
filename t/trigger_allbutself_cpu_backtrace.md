# Function: <code>trigger_allbutself_cpu_backtrace</code>

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
In kernel/watchdog.c (ffffffff8113aaf3)
Location: include/linux/nmi.h:45
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
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
In kernel/watchdog.c (ffffffff81143030)
Location: include/linux/nmi.h:45
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
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
In kernel/watchdog.c (ffffffff8114cd28)
Location: include/linux/nmi.h:62
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8114d643)
Location: include/linux/nmi.h:62
Inline: True
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
In kernel/watchdog.c (ffffffff8114eca8)
Location: include/linux/nmi.h:109
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8114f656)
Location: include/linux/nmi.h:109
Inline: True
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
In kernel/watchdog.c (ffffffff8115b4fe)
Location: include/linux/nmi.h:142
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8115bd6f)
Location: include/linux/nmi.h:142
Inline: True
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
In kernel/watchdog.c (ffffffff8116a7a9)
Location: include/linux/nmi.h:142
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8116aac1)
Location: include/linux/nmi.h:142
Inline: True
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
In kernel/watchdog.c (ffffffff81177072)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81177ab8)
Location: include/linux/nmi.h:150
Inline: True
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
In kernel/watchdog.c (ffffffff811845e7)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8118491e)
Location: include/linux/nmi.h:150
Inline: True
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
In kernel/watchdog.c (ffffffff81190467)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8119079e)
Location: include/linux/nmi.h:150
Inline: True
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
In kernel/watchdog.c (ffffffff811a4fdf)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff811a5349)
Location: include/linux/nmi.h:150
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
In kernel/watchdog.c (ffffffff81be4f86)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81be5027)
Location: include/linux/nmi.h:150
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
In kernel/watchdog.c (ffffffff811a25c2)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81bd6e17)
Location: include/linux/nmi.h:150
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
In kernel/watchdog.c (ffffffff811cbda2)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81cb3f25)
Location: include/linux/nmi.h:150
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
In kernel/watchdog.c (ffffffff811ffb4d)
Location: include/linux/nmi.h:152
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81e64dd3)
Location: include/linux/nmi.h:152
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
In kernel/watchdog.c (ffffffff8124757c)
Location: include/linux/nmi.h:152
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81248229)
Location: include/linux/nmi.h:152
Inline: True
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/watchdog.c (0)
Location: include/linux/nmi.h:179
Inline: True
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
In kernel/watchdog.c (c0446238)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
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
In arch/powerpc/kernel/watchdog.c (c0000000000379cc)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - arch/powerpc/kernel/watchdog.c:watchdog_timer_fn
  - arch/powerpc/kernel/watchdog.c:soft_nmi_interrupt
```
```
In kernel/watchdog.c (c000000000283b10)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
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
In kernel/watchdog.c (0)
Location: include/linux/nmi.h:179
Inline: True
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
In kernel/watchdog.c (ffffffff81188a87)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81188dbe)
Location: include/linux/nmi.h:150
Inline: True
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
In kernel/watchdog.c (ffffffff8117bbc7)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff8117befe)
Location: include/linux/nmi.h:150
Inline: True
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
In kernel/watchdog.c (ffffffff81186857)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff81186b8e)
Location: include/linux/nmi.h:150
Inline: True
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
In kernel/watchdog.c (ffffffff811941a7)
Location: include/linux/nmi.h:150
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/watchdog_hld.c (ffffffff811944de)
Location: include/linux/nmi.h:150
Inline: True
```
</details>
</li>
</ul>

## Differences
