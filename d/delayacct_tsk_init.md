# Function: <code>delayacct_tsk_init</code>

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
In kernel/fork.c (ffffffff8107e979)
Location: include/linux/delayacct.h:65
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff8113de77)
Location: include/linux/delayacct.h:65
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff81080615)
Location: include/linux/delayacct.h:65
Inline: True
```
```
In kernel/delayacct.c (ffffffff81146487)
Location: include/linux/delayacct.h:65
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff81084f2c)
Location: include/linux/delayacct.h:65
Inline: True
```
```
In kernel/delayacct.c (ffffffff811502c7)
Location: include/linux/delayacct.h:65
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff81081e2f)
Location: include/linux/delayacct.h:100
Inline: True
```
```
In kernel/delayacct.c (ffffffff811528e7)
Location: include/linux/delayacct.h:100
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810886cd)
Location: include/linux/delayacct.h:100
Inline: True
```
```
In kernel/delayacct.c (ffffffff8115f117)
Location: include/linux/delayacct.h:100
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff8108c433)
Location: include/linux/delayacct.h:100
Inline: True
```
```
In kernel/delayacct.c (ffffffff8116e0df)
Location: include/linux/delayacct.h:100
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff81093e67)
Location: include/linux/delayacct.h:107
Inline: True
```
```
In kernel/delayacct.c (ffffffff8117bb1f)
Location: include/linux/delayacct.h:107
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810985c6)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff8118893f)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff8109ebb0)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff8119487f)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810a6199)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff811a98af)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810a1abf)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff811a6ecf)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810a2927)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff811a7a0f)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810b404c)
Location: include/linux/delayacct.h:103
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff811d137f)
Location: include/linux/delayacct.h:103
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810ca35a)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff81205a8f)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810e79cf)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff8124dc1f)
Location: include/linux/delayacct.h:85
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810f35ef)
Location: include/linux/delayacct.h:89
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff81264f9f)
Location: include/linux/delayacct.h:89
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810fc99f)
Location: include/linux/delayacct.h:89
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff8127edbf)
Location: include/linux/delayacct.h:89
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffff8000100f37a0)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffff80001020c948)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (c0351ef8)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (c044b2f4)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (c000000000139564)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (c00000000028a590)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffe0000bff0e)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffe00016dc56)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810984d0)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff8118ce9f)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff81086f16)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff8117ff7f)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff81098480)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff8118ac6f)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
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
In kernel/fork.c (ffffffff810a0077)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/delayacct.c (ffffffff811985df)
Location: include/linux/delayacct.h:97
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_init
```
</details>
</li>
</ul>

## Differences
