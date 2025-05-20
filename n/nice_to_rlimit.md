# Function: <code>nice_to_rlimit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81093c7a)
Location: include/linux/sched/prio.h:47
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
```
```
In kernel/sched/core.c (0)
Location: include/linux/sched/prio.h:47
Inline: True
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
In kernel/sys.c (ffffffff81096ead)
Location: include/linux/sched/prio.h:47
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
```
```
In kernel/sched/core.c (ffffffff810ac589)
Location: include/linux/sched/prio.h:47
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
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
In kernel/sys.c (ffffffff8109be5d)
Location: include/linux/sched/prio.h:47
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
```
```
In kernel/sched/core.c (ffffffff810b26a7)
Location: include/linux/sched/prio.h:47
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
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
In kernel/sys.c (ffffffff81098c70)
Location: include/linux/sched/prio.h:47
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
```
```
In kernel/sched/core.c (ffffffff810ae9e5)
Location: include/linux/sched/prio.h:47
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
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
In kernel/sys.c (ffffffff8109f950)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
```
```
In kernel/sched/core.c (ffffffff810b5c3c)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
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
In kernel/sys.c (ffffffff810a63e3)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810bd8b6)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810af0f3)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810c6a91)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810b1134)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810cce39)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810baf74)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810d683f)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810c194e)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810e0c68)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810bc950)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810de0c3)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810be1e2)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810dfc18)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810d1062)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810f4daf)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810e739d)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff81111c29)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff81107fad)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff81138be9)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff811142bd)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff81147a4e)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff8111dcad)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff8115327e)
Location: include/linux/sched/prio.h:32
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffff800010114a1c)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_getpriority
```
```
In kernel/sched/core.c (ffff8000101372a0)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__arm64_sys_nice
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
In kernel/sys.c (c036bcc8)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
```
```
In kernel/sched/core.c (c0386074)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
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
In kernel/sys.c (c00000000015ba74)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
```
```
In kernel/sched/core.c (c000000000182614)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
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
In kernel/sys.c (ffffffe0000d2d50)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_getpriority
```
```
In kernel/sched/core.c (ffffffe0000e793c)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
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
In kernel/sys.c (ffffffff810b52e4)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810d0e33)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810a3c24)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810bf005)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810b4844)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810cef76)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
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
In kernel/sys.c (ffffffff810b9769)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
```
```
In kernel/sched/core.c (ffffffff810d7ea4)
Location: include/linux/sched/prio.h:48
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
```
</details>
</li>
</ul>

## Differences
