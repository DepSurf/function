# Function: <code>acpi_unregister_wakeup_handler</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_unregister_wakeup_handler(bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff81682960)
Location: drivers/acpi/wakeup.c:145
Inline: False
```
**Symbols:**

```
ffffffff81682960-ffffffff816829e1: acpi_unregister_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_unregister_wakeup_handler(bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff816a0fc0)
Location: drivers/acpi/wakeup.c:143
Inline: False
```
**Symbols:**

```
ffffffff816a0fc0-ffffffff816a1041: acpi_unregister_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_unregister_wakeup_handler(bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff81683db0)
Location: drivers/acpi/wakeup.c:143
Inline: False
```
**Symbols:**

```
ffffffff81683db0-ffffffff81683e31: acpi_unregister_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_unregister_wakeup_handler(bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff816f8f60)
Location: drivers/acpi/wakeup.c:143
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
```
**Symbols:**

```
ffffffff816f8f60-ffffffff816f8fe1: acpi_unregister_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_unregister_wakeup_handler(bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff81826260)
Location: drivers/acpi/wakeup.c:143
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
```
**Symbols:**

```
ffffffff81826260-ffffffff818262ed: acpi_unregister_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_unregister_wakeup_handler(bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff81957c20)
Location: drivers/acpi/wakeup.c:143
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
```
**Symbols:**

```
ffffffff81957c20-ffffffff81957cad: acpi_unregister_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_unregister_wakeup_handler(bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff8199e0e0)
Location: drivers/acpi/wakeup.c:143
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
```
**Symbols:**

```
ffffffff8199e0e0-ffffffff8199e16d: acpi_unregister_wakeup_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_unregister_wakeup_handler(bool (*wakeup)(void *), void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/wakeup.c (ffffffff819e6780)
Location: drivers/acpi/wakeup.c:143
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_remove
```
**Symbols:**

```
ffffffff819e6780-ffffffff819e680d: acpi_unregister_wakeup_handler (STB_GLOBAL)
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
