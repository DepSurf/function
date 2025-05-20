# Function: <code>timekeeping_adjust</code>

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
In kernel/time/timekeeping.c (ffffffff810f648a)
Location: kernel/time/timekeeping.c:1900
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_wall_time
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
In kernel/time/timekeeping.c (ffffffff810fd697)
Location: kernel/time/timekeeping.c:1905
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_wall_time
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
In kernel/time/timekeeping.c (ffffffff81100487)
Location: kernel/time/timekeeping.c:1918
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_wall_time
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
In kernel/time/timekeeping.c (ffffffff81102666)
Location: kernel/time/timekeeping.c:1909
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_wall_time
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
In kernel/time/timekeeping.c (ffffffff8110d609)
Location: kernel/time/timekeeping.c:1944
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_wall_time
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
In kernel/time/timekeeping.c (ffffffff811190d1)
Location: kernel/time/timekeeping.c:1879
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:update_wall_time
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
In kernel/time/timekeeping.c (ffffffff81123f70)
Location: kernel/time/timekeeping.c:1889
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (ffffffff8112e53e)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (ffffffff8113a4ee)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1898
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81148390-ffffffff811484e1: timekeeping_adjust.constprop.0 (STB_LOCAL)
ffffffff8114a742-ffffffff8114a766: timekeeping_adjust.constprop.0.cold (STB_LOCAL)
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
In kernel/time/timekeeping.c (0)
Location: kernel/time/timekeeping.c:1969
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81144800-ffffffff81144951: timekeeping_adjust.constprop.0 (STB_LOCAL)
ffffffff81be3866-ffffffff81be388a: timekeeping_adjust.constprop.0.cold (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffffffff81146ed3)
Location: kernel/time/timekeeping.c:1980
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
Location: kernel/time/timekeeping.c:1981
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81169020-ffffffff81169196: timekeeping_adjust.constprop.0 (STB_LOCAL)
ffffffff81cb0a63-ffffffff81cb0af9: timekeeping_adjust.constprop.0.cold (STB_LOCAL)
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
Location: kernel/time/timekeeping.c:2002
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff8119cc40-ffffffff8119cdd2: timekeeping_adjust.constprop.0 (STB_LOCAL)
ffffffff81e61ffb-ffffffff81e62091: timekeeping_adjust.constprop.0.cold (STB_LOCAL)
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
Location: kernel/time/timekeeping.c:2002
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff811db6f0-ffffffff811db8b3: timekeeping_adjust.constprop.0 (STB_LOCAL)
ffffffff8205ae97-ffffffff8205aefb: timekeeping_adjust.constprop.0.cold (STB_LOCAL)
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
Location: kernel/time/timekeeping.c:2002
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff811efc40-ffffffff811efe03: timekeeping_adjust.constprop.0 (STB_LOCAL)
ffffffff820d974b-ffffffff820d97af: timekeeping_adjust.constprop.0.cold (STB_LOCAL)
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
Location: kernel/time/timekeeping.c:2002
Inline: True
Direct callers:
  - kernel/time/timekeeping.c:timekeeping_advance
```
**Symbols:**

```
ffffffff81205d80-ffffffff81205f43: timekeeping_adjust.constprop.0 (STB_LOCAL)
ffffffff821b504a-ffffffff821b50ae: timekeeping_adjust.constprop.0.cold (STB_LOCAL)
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
In kernel/time/timekeeping.c (ffff8000101a4980)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (c03eec7c)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (c00000000020647c)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (ffffffe000130fae)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (ffffffff81132c9e)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (ffffffff811256fe)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (ffffffff811309be)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
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
In kernel/time/timekeeping.c (ffffffff8113d3de)
Location: kernel/time/timekeeping.c:1899
Inline: True
Inline callers:
  - kernel/time/timekeeping.c:timekeeping_advance
```
</details>
</li>
</ul>

## Differences
