# Function: <code>dpm_noirq_begin</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void dpm_noirq_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81657c00)
Location: drivers/base/power/main.c:1239
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff816578f0-ffffffff8165790a: dpm_noirq_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void dpm_noirq_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff81693705)
Location: drivers/base/power/main.c:1375
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff81693480-ffffffff8169349a: dpm_noirq_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void dpm_noirq_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816b3d85)
Location: drivers/base/power/main.c:1377
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
Direct callers:
  - kernel/power/suspend.c:suspend_devices_and_enter
```
**Symbols:**

```
ffffffff816b3b00-ffffffff816b3b1a: dpm_noirq_begin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dpm_noirq_begin();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/main.c (ffffffff816edb65)
Location: drivers/base/power/main.c:1365
Inline: True
Inline callers:
  - drivers/base/power/main.c:dpm_suspend_noirq
Direct callers:
  - kernel/power/suspend.c:suspend_enter
```
**Symbols:**

```
ffffffff816ed890-ffffffff816ed8aa: dpm_noirq_begin (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
