# Function: <code>acpi_sleep_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8147bace)
Location: drivers/acpi/sleep.c:57
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_power_off_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff8147bace-ffffffff8147bb03: acpi_sleep_prepare.part.1 (STB_LOCAL)
ffffffff8147bb03-ffffffff8147bb36: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ca29a)
Location: drivers/acpi/sleep.c:80
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff814ca0ea-ffffffff814ca11f: acpi_sleep_prepare.part.1 (STB_LOCAL)
ffffffff814ca2ed-ffffffff814ca322: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ec1b6)
Location: drivers/acpi/sleep.c:63
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff814ec045-ffffffff814ec07a: acpi_sleep_prepare.part.1 (STB_LOCAL)
ffffffff814ec209-ffffffff814ec23e: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814f8456)
Location: drivers/acpi/sleep.c:63
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff814f83a0-ffffffff814f83d7: acpi_sleep_prepare.part.2 (STB_LOCAL)
ffffffff814f83e0-ffffffff814f8419: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8153a206)
Location: drivers/acpi/sleep.c:63
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff8153a120-ffffffff8153a157: acpi_sleep_prepare.part.2 (STB_LOCAL)
ffffffff8153a160-ffffffff8153a199: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8156ff95)
Location: drivers/acpi/sleep.c:63
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff8156feb0-ffffffff8156fee7: acpi_sleep_prepare.part.2 (STB_LOCAL)
ffffffff8156fef0-ffffffff8156ff29: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81587b55)
Location: drivers/acpi/sleep.c:63
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff81587a70-ffffffff81587aa7: acpi_sleep_prepare.part.2 (STB_LOCAL)
ffffffff81587ab0-ffffffff81587ae9: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b8595)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff815b84b0-ffffffff815b84ee: acpi_sleep_prepare.part.0 (STB_LOCAL)
ffffffff815b84f0-ffffffff815b852d: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815d9805)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff815d9720-ffffffff815d975e: acpi_sleep_prepare.part.0 (STB_LOCAL)
ffffffff815d9760-ffffffff815d979d: acpi_sleep_prepare (STB_LOCAL)
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
In drivers/acpi/sleep.c (ffffffff81683a25)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff81683970-ffffffff816839b0: acpi_sleep_prepare.part.0 (STB_LOCAL)
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
In drivers/acpi/sleep.c (ffffffff816a1915)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff816a1860-ffffffff816a18a0: acpi_sleep_prepare.part.0 (STB_LOCAL)
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
In drivers/acpi/sleep.c (ffffffff816848d5)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff816847c0-ffffffff81684800: acpi_sleep_prepare.part.0 (STB_LOCAL)
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
In drivers/acpi/sleep.c (ffffffff816f9b85)
Location: drivers/acpi/sleep.c:63
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff816f9a70-ffffffff816f9ab0: acpi_sleep_prepare.part.0 (STB_LOCAL)
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
In drivers/acpi/sleep.c (ffffffff81eb68bc)
Location: drivers/acpi/sleep.c:63
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff81eb687f-ffffffff81eb68b7: acpi_sleep_prepare.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81958905)
Location: drivers/acpi/sleep.c:67
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff819580e0-ffffffff81958143: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8199ed85)
Location: drivers/acpi/sleep.c:67
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff8199e5c0-ffffffff8199e623: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff819e7425)
Location: drivers/acpi/sleep.c:67
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff819e6c60-ffffffff819e6cc3: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/acpi/sleep.c (ffffffff815cc1b5)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_pm_prepare
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff815cc110-ffffffff815cc14e: acpi_sleep_prepare.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b5385)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff815b52d0-ffffffff815b5308: acpi_sleep_prepare.part.0 (STB_LOCAL)
ffffffff815b5310-ffffffff815b534d: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cdae5)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff815cda00-ffffffff815cda3e: acpi_sleep_prepare.part.0 (STB_LOCAL)
ffffffff815cda40-ffffffff815cda7d: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_sleep_prepare(u32 acpi_state);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815e7985)
Location: drivers/acpi/sleep.c:61
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
Direct callers:
  - drivers/acpi/sleep.c:acpi_power_off_prepare
  - drivers/acpi/sleep.c:acpi_hibernation_begin_old
  - drivers/acpi/sleep.c:acpi_pm_prepare
```
**Symbols:**

```
ffffffff815e78a0-ffffffff815e78de: acpi_sleep_prepare.part.0 (STB_LOCAL)
ffffffff815e78e0-ffffffff815e791d: acpi_sleep_prepare (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
