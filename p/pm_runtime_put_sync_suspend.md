# Function: <code>pm_runtime_put_sync_suspend</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185bfa0)
Location: include/linux/pm_runtime.h:244
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff8189fe5d)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff818d23cd)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff819a4b0d)
Location: include/linux/pm_runtime.h:255
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff819a7bad)
Location: include/linux/pm_runtime.h:464
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff8198c8ad)
Location: include/linux/pm_runtime.h:464
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff81a37f0d)
Location: include/linux/pm_runtime.h:474
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff81ba4aee)
Location: include/linux/pm_runtime.h:503
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff81d46d2e)
Location: include/linux/pm_runtime.h:507
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff81db151e)
Location: include/linux/pm_runtime.h:507
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff81e698ae)
Location: include/linux/pm_runtime.h:505
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/tty/serial/8250/8250_dw.c (ffff800010891050)
Location: include/linux/pm_runtime.h:245
Inline: True
```
```
In drivers/tty/serial/8250/8250_mtk.c (ffff800010892248)
Location: include/linux/pm_runtime.h:245
Inline: True
```
```
In drivers/mmc/core/core.c (ffff800010b2d8f4)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/tty/serial/8250/8250_mtk.c (c098d5d8)
Location: include/linux/pm_runtime.h:245
Inline: True
```
```
In drivers/power/avs/smartreflex.c (c0ba9c2c)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/power/avs/smartreflex.c:sr_disable
```
```
In drivers/mmc/core/core.c (c0c06cf8)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (c000000000c23f3c)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffe00070574a)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff81875d8d)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff818c722d)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
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
In drivers/mmc/core/core.c (ffffffff818e3cdd)
Location: include/linux/pm_runtime.h:245
Inline: True
Inline callers:
  - drivers/mmc/core/core.c:mmc_release_host
```
</details>
</li>
</ul>

## Differences
