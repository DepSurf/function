# Function: <code>acpi_get_wakeup_address</code>

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
long unsigned int acpi_get_wakeup_address();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/sleep.c (ffffffff81068320)
Location: arch/x86/kernel/acpi/sleep.c:35
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff81068320-ffffffff81068335: acpi_get_wakeup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int acpi_get_wakeup_address();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106a000)
Location: arch/x86/kernel/acpi/sleep.c:35
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff8106a000-ffffffff8106a015: acpi_get_wakeup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int acpi_get_wakeup_address();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/sleep.c (ffffffff8106aad0)
Location: arch/x86/kernel/acpi/sleep.c:35
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff8106aad0-ffffffff8106aae5: acpi_get_wakeup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int acpi_get_wakeup_address();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/sleep.c (ffffffff81075430)
Location: arch/x86/kernel/acpi/sleep.c:35
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff81075430-ffffffff81075445: acpi_get_wakeup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int acpi_get_wakeup_address();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/sleep.c (ffffffff81083e90)
Location: arch/x86/kernel/acpi/sleep.c:36
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_suspend_begin_old
```
**Symbols:**

```
ffffffff81083e90-ffffffff81083ea9: acpi_get_wakeup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int acpi_get_wakeup_address();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/sleep.c (ffffffff81096d00)
Location: arch/x86/kernel/acpi/sleep.c:36
Inline: False
```
**Symbols:**

```
ffffffff81096d00-ffffffff81096d19: acpi_get_wakeup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int acpi_get_wakeup_address();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/sleep.c (ffffffff81099e20)
Location: arch/x86/kernel/acpi/sleep.c:37
Inline: False
```
**Symbols:**

```
ffffffff81099e20-ffffffff81099e39: acpi_get_wakeup_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int acpi_get_wakeup_address();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/acpi/sleep.c (ffffffff810a1650)
Location: arch/x86/kernel/acpi/sleep.c:37
Inline: False
```
**Symbols:**

```
ffffffff810a1650-ffffffff810a1669: acpi_get_wakeup_address (STB_GLOBAL)
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
