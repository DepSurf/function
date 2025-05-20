# Function: <code>dev_to_psd</code>

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
In drivers/base/power/common.c (ffffffff81554a9e)
Location: include/linux/device.h:906
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff8155d135)
Location: include/linux/device.h:906
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_resume
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
In drivers/base/power/common.c (ffffffff815a6afe)
Location: include/linux/device.h:922
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff815b1369)
Location: include/linux/device.h:922
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff815d52be)
Location: include/linux/device.h:1031
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff815e0649)
Location: include/linux/device.h:1031
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff815e9d6e)
Location: include/linux/device.h:1035
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff815f54e4)
Location: include/linux/device.h:1035
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff8165110e)
Location: include/linux/device.h:1033
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff8165d404)
Location: include/linux/device.h:1033
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff8168c9ce)
Location: include/linux/device.h:1078
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff81699135)
Location: include/linux/device.h:1078
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff816acc1e)
Location: include/linux/device.h:1131
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff816b9995)
Location: include/linux/device.h:1131
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff816e66de)
Location: include/linux/device.h:1154
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff816f3cb5)
Location: include/linux/device.h:1154
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff8170aaae)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff817180b5)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff817c5abe)
Location: include/linux/device.h:703
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff817d3be5)
Location: include/linux/device.h:703
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff817da5ce)
Location: include/linux/device.h:671
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff817e8635)
Location: include/linux/device.h:671
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff817be97e)
Location: include/linux/device.h:677
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff817ccee8)
Location: include/linux/device.h:677
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff81848cfe)
Location: include/linux/device.h:694
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff818574c8)
Location: include/linux/device.h:694
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff8198dac0)
Location: include/linux/device.h:769
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff8199df38)
Location: include/linux/device.h:769
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff81afd9c0)
Location: include/linux/device.h:766
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff81b0f748)
Location: include/linux/device.h:766
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff81b4bdb0)
Location: include/linux/device.h:892
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff81b5d808)
Location: include/linux/device.h:892
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff81ba41f0)
Location: include/linux/device.h:924
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb10e8)
Location: include/linux/device.h:924
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffff8000108f9430)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffff80001090b788)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (c09e4a58)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (c09f4c48)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (c000000000995604)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
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
In drivers/base/power/common.c (ffffffe000588e66)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffe000590bf8)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff816d01fe)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff816de3e5)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff816ab52e)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff816b8a45)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff816fe76e)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff8170bd75)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
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
In drivers/base/power/common.c (ffffffff81718e90)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_put_subsys_data
```
```
In drivers/base/power/clock_ops.c (ffffffff81726ba5)
Location: include/linux/device.h:1396
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:pm_clk_resume
  - drivers/base/power/clock_ops.c:pm_clk_suspend
  - drivers/base/power/clock_ops.c:pm_clk_destroy
  - drivers/base/power/clock_ops.c:pm_clk_init
  - drivers/base/power/clock_ops.c:pm_clk_remove_clk
  - drivers/base/power/clock_ops.c:pm_clk_remove
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
</details>
</li>
</ul>

## Differences
