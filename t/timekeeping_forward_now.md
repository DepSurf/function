# Function: <code>timekeeping_forward_now</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810f4ea0)
Location: kernel/time/timekeeping.c:614
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
```
**Symbols:**

```
ffffffff810f4ea0-ffffffff810f4f8e: timekeeping_forward_now.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fc060)
Location: kernel/time/timekeeping.c:619
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff810fc060-ffffffff810fc14b: timekeeping_forward_now.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff810fef60)
Location: kernel/time/timekeeping.c:648
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff810fef60-ffffffff810ff04b: timekeeping_forward_now.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811010d0)
Location: kernel/time/timekeeping.c:679
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff811010d0-ffffffff811011c3: timekeeping_forward_now.constprop.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8110bf00)
Location: kernel/time/timekeeping.c:683
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff8110bf00-ffffffff8110bff6: timekeeping_forward_now.constprop.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81117d70)
Location: kernel/time/timekeeping.c:684
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81117d70-ffffffff81117e64: timekeeping_forward_now.constprop.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81123390)
Location: kernel/time/timekeeping.c:691
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81123390-ffffffff81123484: timekeeping_forward_now.constprop.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8112db90)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8112db90-ffffffff8112dc8e: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81139b40)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81139b40-ffffffff81139c3e: timekeeping_forward_now.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81148b90)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81148b90-ffffffff81148c8a: timekeeping_forward_now.constprop.0 (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81145000)
Location: kernel/time/timekeeping.c:775
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81145000-ffffffff811450fa: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81145ef0)
Location: kernel/time/timekeeping.c:775
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81145ef0-ffffffff81145fe7: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:775
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8116a150-ffffffff8116a23c: timekeeping_forward_now.constprop.0 (STB_LOCAL)
ffffffff81cb0e9f-ffffffff81cb0f5a: timekeeping_forward_now.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:794
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff8119de90-ffffffff8119df8a: timekeeping_forward_now.constprop.0 (STB_LOCAL)
ffffffff81e62430-ffffffff81e624eb: timekeeping_forward_now.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:794
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff811dca40-ffffffff811dcb3a: timekeeping_forward_now.constprop.0 (STB_LOCAL)
ffffffff8205b27d-ffffffff8205b338: timekeeping_forward_now.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:794
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff811f0f60-ffffffff811f1057: timekeeping_forward_now.constprop.0 (STB_LOCAL)
ffffffff820d9b35-ffffffff820d9be7: timekeeping_forward_now.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:794
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
  - kernel/time/timekeeping.c:do_settimeofday64
```
**Symbols:**

```
ffffffff812070a0-ffffffff81207197: timekeeping_forward_now.constprop.0 (STB_LOCAL)
ffffffff821b5434-ffffffff821b54e6: timekeeping_forward_now.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffff8000101a3c58)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffff8000101a3c58-ffff8000101a3d38: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (c03ee034)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
c03ee034-c03ee1dc: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (c000000000205710)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
c000000000205710-c000000000205848: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffe00013068a)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffe00013068a-ffffffe00013072c: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff811322f0)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff811322f0-ffffffff811323ee: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81124d50)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81124d50-ffffffff81124e4e: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff81130010)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff81130010-ffffffff8113010e: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/timekeeping.c (ffffffff8113ca30)
Location: kernel/time/timekeeping.c:697
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_suspend
  - kernel/time/timekeeping.c:timekeeping_inject_sleeptime64
  - kernel/time/timekeeping.c:change_clocksource
  - kernel/time/timekeeping.c:timekeeping_inject_offset
```
**Symbols:**

```
ffffffff8113ca30-ffffffff8113cb2e: timekeeping_forward_now.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
