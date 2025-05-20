# Function: <code>__clocksource_suspend_select</code>

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
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __clocksource_suspend_select(struct clocksource *cs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/clocksource.c (ffffffff81126189)
Location: kernel/time/clocksource.c:461
Inline: True
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffffffff81126160-ffffffff811261a8: __clocksource_suspend_select (STB_LOCAL)
ffffffff81126fd8-ffffffff81126fed: __clocksource_suspend_select.cold.13 (STB_LOCAL)
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
In kernel/time/clocksource.c (ffffffff81130f7d)
Location: kernel/time/clocksource.c:461
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffffffff81130b90-ffffffff81130bd1: __clocksource_suspend_select.part.0 (STB_LOCAL)
ffffffff811319a7-ffffffff811319bc: __clocksource_suspend_select.part.0.cold (STB_LOCAL)
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
In kernel/time/clocksource.c (ffffffff8113cebd)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffffffff8113cad0-ffffffff8113cb11: __clocksource_suspend_select.part.0 (STB_LOCAL)
ffffffff8113d8f7-ffffffff8113d90c: __clocksource_suspend_select.part.0.cold (STB_LOCAL)
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
In kernel/time/clocksource.c (ffffffff8114c4b0)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
  - kernel/time/clocksource.c:clocksource_suspend_select
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
In kernel/time/clocksource.c (ffffffff81148910)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
  - kernel/time/clocksource.c:clocksource_suspend_select
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
In kernel/time/clocksource.c (ffffffff81149e0b)
Location: kernel/time/clocksource.c:569
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
  - kernel/time/clocksource.c:clocksource_suspend_select
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
In kernel/time/clocksource.c (ffffffff8116d6db)
Location: kernel/time/clocksource.c:681
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
  - kernel/time/clocksource.c:clocksource_suspend_select
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
In kernel/time/clocksource.c (ffffffff811a17ab)
Location: kernel/time/clocksource.c:687
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
  - kernel/time/clocksource.c:clocksource_suspend_select
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
In kernel/time/clocksource.c (ffffffff811e04cb)
Location: kernel/time/clocksource.c:706
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
  - kernel/time/clocksource.c:clocksource_suspend_select
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
In kernel/time/clocksource.c (ffffffff811f49cb)
Location: kernel/time/clocksource.c:717
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
  - kernel/time/clocksource.c:clocksource_suspend_select
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
In kernel/time/clocksource.c (ffffffff8120ab0b)
Location: kernel/time/clocksource.c:740
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
  - kernel/time/clocksource.c:clocksource_suspend_select
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
In kernel/time/clocksource.c (ffff8000101a6f5c)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffff8000101a6bd0-ffff8000101a6c3c: __clocksource_suspend_select.part.0 (STB_LOCAL)
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
In kernel/time/clocksource.c (c03f25f0)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
c03f1c18-c03f1c88: __clocksource_suspend_select.part.0 (STB_LOCAL)
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
In kernel/time/clocksource.c (c000000000209888)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
c000000000209380-c000000000209410: __clocksource_suspend_select.part.0 (STB_LOCAL)
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
In kernel/time/clocksource.c (ffffffe000132fe6)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffffffe000132cfa-ffffffe000132d4c: __clocksource_suspend_select.part.0 (STB_LOCAL)
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
In kernel/time/clocksource.c (ffffffff8113566d)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffffffff81135280-ffffffff811352c1: __clocksource_suspend_select.part.0 (STB_LOCAL)
ffffffff811360a7-ffffffff811360bc: __clocksource_suspend_select.part.0.cold (STB_LOCAL)
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
In kernel/time/clocksource.c (ffffffff811280cd)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffffffff81127ce0-ffffffff81127d21: __clocksource_suspend_select.part.0 (STB_LOCAL)
ffffffff81128af7-ffffffff81128b0c: __clocksource_suspend_select.part.0.cold (STB_LOCAL)
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
In kernel/time/clocksource.c (ffffffff8113338d)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffffffff81132fa0-ffffffff81132fe1: __clocksource_suspend_select.part.0 (STB_LOCAL)
ffffffff81133dc7-ffffffff81133ddc: __clocksource_suspend_select.part.0.cold (STB_LOCAL)
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
In kernel/time/clocksource.c (ffffffff8113fdad)
Location: kernel/time/clocksource.c:468
Inline: True
Inline callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
Direct callers:
  - kernel/time/clocksource.c:__clocksource_register_scale
  - kernel/time/clocksource.c:clocksource_suspend_select
```
**Symbols:**

```
ffffffff8113f9c0-ffffffff8113fa01: __clocksource_suspend_select.part.0 (STB_LOCAL)
ffffffff811407e7-ffffffff811407fc: __clocksource_suspend_select.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
