# Function: <code>hv_stimer_alloc</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hv_stimer_alloc(int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818bc7e0)
Location: drivers/clocksource/hyperv_timer.c:148
Inline: False
```
**Symbols:**

```
ffffffff818bc7e0-ffffffff818bc872: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hv_stimer_alloc(int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818ef2e0)
Location: drivers/clocksource/hyperv_timer.c:149
Inline: False
```
**Symbols:**

```
ffffffff818ef2e0-ffffffff818ef372: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int hv_stimer_alloc();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c2fa0)
Location: drivers/clocksource/hyperv_timer.c:173
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff819c2fa0-ffffffff819c307f: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int hv_stimer_alloc();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819c3390)
Location: drivers/clocksource/hyperv_timer.c:173
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_stimer_setup_percpu_clockev
```
**Symbols:**

```
ffffffff819c3390-ffffffff819c346f: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int hv_stimer_alloc(bool have_percpu_irqs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff819a7b51)
Location: drivers/clocksource/hyperv_timer.c:234
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_stimer_setup_percpu_clockev
```
**Symbols:**

```
ffffffff81c1f629-ffffffff81c1f66a: hv_stimer_alloc.cold (STB_LOCAL)
ffffffff819a7b00-ffffffff819a7c47: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hv_stimer_alloc(bool have_percpu_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:234
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_stimer_setup_percpu_clockev
```
**Symbols:**

```
ffffffff81d30d2d-ffffffff81d30d6e: hv_stimer_alloc.cold (STB_LOCAL)
ffffffff81a550b0-ffffffff81a551fd: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hv_stimer_alloc(bool have_percpu_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (0)
Location: drivers/clocksource/hyperv_timer.c:234
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_stimer_setup_percpu_clockev
```
**Symbols:**

```
ffffffff81efd16b-ffffffff81efd1ac: hv_stimer_alloc.cold (STB_LOCAL)
ffffffff81bc47e0-ffffffff81bc4951: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_stimer_alloc(bool have_percpu_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81d6a030)
Location: drivers/clocksource/hyperv_timer.c:235
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_stimer_setup_percpu_clockev
```
**Symbols:**

```
ffffffff81d6a030-ffffffff81d6a1d7: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_stimer_alloc(bool have_percpu_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81dd53f0)
Location: drivers/clocksource/hyperv_timer.c:246
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_stimer_setup_percpu_clockev
```
**Symbols:**

```
ffffffff81dd53f0-ffffffff81dd5597: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_stimer_alloc(bool have_percpu_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81e8d540)
Location: drivers/clocksource/hyperv_timer.c:246
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hv_stimer_setup_percpu_clockev
```
**Symbols:**

```
ffffffff81e8d540-ffffffff81e8d6e7: hv_stimer_alloc (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int hv_stimer_alloc(int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818906b0)
Location: drivers/clocksource/hyperv_timer.c:149
Inline: False
```
**Symbols:**

```
ffffffff818906b0-ffffffff81890742: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hv_stimer_alloc(int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818498e0)
Location: drivers/clocksource/hyperv_timer.c:149
Inline: False
Direct callers:
  - drivers/hv/vmbus_drv.c:hv_acpi_init
```
**Symbols:**

```
ffffffff818498e0-ffffffff81849972: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hv_stimer_alloc(int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff818e4110)
Location: drivers/clocksource/hyperv_timer.c:149
Inline: False
```
**Symbols:**

```
ffffffff818e4110-ffffffff818e41a2: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hv_stimer_alloc(int sint);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clocksource/hyperv_timer.c (ffffffff81900d70)
Location: drivers/clocksource/hyperv_timer.c:149
Inline: False
```
**Symbols:**

```
ffffffff81900d70-ffffffff81900e02: hv_stimer_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int sint</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool have_percpu_irqs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
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
