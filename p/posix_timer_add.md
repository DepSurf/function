# Function: <code>posix_timer_add</code>

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
In kernel/time/posix-timers.c (ffffffff810f143c)
Location: kernel/time/posix-timers.c:176
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
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
In kernel/time/posix-timers.c (ffffffff810f84c3)
Location: kernel/time/posix-timers.c:176
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
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
In kernel/time/posix-timers.c (ffffffff81105e53)
Location: kernel/time/posix-timers.c:176
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:SyS_timer_create
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
In kernel/time/posix-timers.c (ffffffff81107f30)
Location: kernel/time/posix-timers.c:167
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811130e0)
Location: kernel/time/posix-timers.c:168
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff8111f858)
Location: kernel/time/posix-timers.c:168
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff8112b022)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81136099)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81142139)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811508a0)
Location: kernel/time/posix-timers.c:140
Inline: True
Direct callers:
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff811508a0-ffffffff811509c1: posix_timer_add.constprop.0 (STB_LOCAL)
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
In kernel/time/posix-timers.c (ffffffff8114cb20)
Location: kernel/time/posix-timers.c:140
Inline: True
Direct callers:
  - kernel/time/posix-timers.c:do_timer_create
```
**Symbols:**

```
ffffffff8114cb20-ffffffff8114cc41: posix_timer_add.constprop.0 (STB_LOCAL)
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
In kernel/time/posix-timers.c (ffffffff8114f129)
Location: kernel/time/posix-timers.c:140
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811732e6)
Location: kernel/time/posix-timers.c:140
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811a6605)
Location: kernel/time/posix-timers.c:140
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811e61a5)
Location: kernel/time/posix-timers.c:140
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811fa7eb)
Location: kernel/time/posix-timers.c:97
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff812109db)
Location: kernel/time/posix-timers.c:97
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffff8000101ac250)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (c03f65e8)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (c00000000020fe94)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffe000136184)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff8113a8e9)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff8112d339)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff81138609)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
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
In kernel/time/posix-timers.c (ffffffff811451b8)
Location: kernel/time/posix-timers.c:138
Inline: True
Inline callers:
  - kernel/time/posix-timers.c:do_timer_create
```
</details>
</li>
</ul>

## Differences
