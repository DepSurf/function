# Function: <code>init_timer_on_stack_key</code>

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
In arch/x86/kernel/hpet.c (ffffffff810625fc)
Location: include/linux/timer.h:98
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_notify
```
```
In kernel/time/timer.c (ffffffff818233ad)
Location: include/linux/timer.h:98
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
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
In arch/x86/kernel/hpet.c (ffffffff810623f6)
Location: include/linux/timer.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/time/timer.c (ffffffff8189de2d)
Location: include/linux/timer.h:105
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
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
In arch/x86/kernel/hpet.c (ffffffff81065466)
Location: include/linux/timer.h:105
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/time/timer.c (ffffffff818d2cdd)
Location: include/linux/timer.h:105
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
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
In arch/x86/kernel/hpet.c (ffffffff81064396)
Location: include/linux/timer.h:102
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/time/timer.c (ffffffff81909efa)
Location: include/linux/timer.h:102
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
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
In arch/x86/kernel/hpet.c (ffffffff81068516)
Location: include/linux/timer.h:91
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/time/timer.c (ffffffff81994238)
Location: include/linux/timer.h:91
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
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
In arch/x86/kernel/hpet.c (ffffffff8106b0bc)
Location: include/linux/timer.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/time/timer.c (ffffffff819f07b8)
Location: include/linux/timer.h:89
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
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
In arch/x86/kernel/hpet.c (ffffffff81070e4c)
Location: include/linux/timer.h:89
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_cpuhp_online
```
```
In kernel/time/timer.c (ffffffff81a2bb38)
Location: include/linux/timer.h:89
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
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
In kernel/time/timer.c (ffffffff81a9bd69)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
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
In kernel/time/timer.c (ffffffff81ad36b9)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff816bc77e)
Location: include/linux/timer.h:100
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
In kernel/time/timer.c (ffffffff81bcb7c3)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff8177118a)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
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
In kernel/time/timer.c (ffffffff81c44662)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff8178c1ba)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
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
In kernel/time/timer.c (ffffffff81c378d2)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff8176f0f6)
Location: include/linux/timer.h:101
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
In kernel/time/timer.c (ffffffff81d56192)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff817f4933)
Location: include/linux/timer.h:101
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
In kernel/time/timer.c (ffffffff81f281a4)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff81ec2d12)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
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
In kernel/time/timer.c (ffffffff820d3d94)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff81a94d9c)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
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
In kernel/time/timer.c (ffffffff82158014)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff81ae05bc)
Location: include/linux/timer.h:101
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
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
In kernel/time/timer.c (ffffffff8223ae84)
Location: include/linux/timer.h:86
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff81b339bc)
Location: include/linux/timer.h:86
Inline: True
Inline callers:
  - drivers/char/random.c:try_to_generate_entropy
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
In kernel/time/timer.c (ffff800010da6374)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffff8000108ae09c)
Location: include/linux/timer.h:100
Inline: True
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
In kernel/time/timer.c (c0e9df88)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (c09a98f8)
Location: include/linux/timer.h:100
Inline: True
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
In kernel/time/timer.c (c000000000ee8960)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (c0000000009460e0)
Location: include/linux/timer.h:100
Inline: True
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
In kernel/time/timer.c (ffffffe0008c86a4)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffe000561870)
Location: include/linux/timer.h:100
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
In kernel/time/timer.c (ffffffff81a72529)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff816821de)
Location: include/linux/timer.h:100
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
In kernel/time/timer.c (ffffffff81a2e8f9)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff8166005e)
Location: include/linux/timer.h:100
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
In kernel/time/timer.c (ffffffff81ade939)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff816b05be)
Location: include/linux/timer.h:100
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
In kernel/time/timer.c (ffffffff81aeadb9)
Location: include/linux/timer.h:100
Inline: True
Inline callers:
  - kernel/time/timer.c:schedule_timeout
```
```
In drivers/char/random.c (ffffffff816cad00)
Location: include/linux/timer.h:100
Inline: True
```
</details>
</li>
</ul>

## Differences
