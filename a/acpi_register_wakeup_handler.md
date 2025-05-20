# Function: <code>acpi_register_wakeup_handler</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_wakeup_handler(int wake_irq, bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff816829f0)
Location: drivers/acpi/wakeup.c:113
Inline: True
```
**Symbols:**

```
ffffffff816829f0-ffffffff81682a97: acpi_register_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_wakeup_handler(int wake_irq, bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff816a1050)
Location: drivers/acpi/wakeup.c:111
Inline: True
```
**Symbols:**

```
ffffffff816a1050-ffffffff816a10f7: acpi_register_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_wakeup_handler(int wake_irq, bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff81683e40)
Location: drivers/acpi/wakeup.c:111
Inline: True
```
**Symbols:**

```
ffffffff81683e40-ffffffff81683ee7: acpi_register_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_register_wakeup_handler(int wake_irq, bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff816f8ff0)
Location: drivers/acpi/wakeup.c:111
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff816f8ff0-ffffffff816f9097: acpi_register_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_register_wakeup_handler(int wake_irq, bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff818261b0)
Location: drivers/acpi/wakeup.c:111
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff818261b0-ffffffff81826256: acpi_register_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_register_wakeup_handler(int wake_irq, bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff81957b60)
Location: drivers/acpi/wakeup.c:111
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff81957b60-ffffffff81957c06: acpi_register_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_register_wakeup_handler(int wake_irq, bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff8199e020)
Location: drivers/acpi/wakeup.c:111
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff8199e020-ffffffff8199e0c6: acpi_register_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_register_wakeup_handler(int wake_irq, bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff819e6690)
Location: drivers/acpi/wakeup.c:111
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff819e6690-ffffffff819e6764: acpi_register_wakeup_handler (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
