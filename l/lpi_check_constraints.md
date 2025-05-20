# Function: <code>lpi_check_constraints</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8153953d)
Location: drivers/acpi/sleep.c:838
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_s2idle_wake
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
In drivers/acpi/sleep.c (ffffffff8156f686)
Location: drivers/acpi/sleep.c:868
Inline: True
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
In drivers/acpi/sleep.c (ffffffff81587266)
Location: drivers/acpi/sleep.c:865
Inline: True
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
In drivers/acpi/sleep.c (ffffffff815b7ed6)
Location: drivers/acpi/sleep.c:855
Inline: True
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
In drivers/acpi/sleep.c (ffffffff815d9173)
Location: drivers/acpi/sleep.c:846
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void lpi_check_constraints();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81682d50)
Location: drivers/acpi/sleep.c:849
Inline: False
```
**Symbols:**

```
ffffffff81682d50-ffffffff81682ec4: lpi_check_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void lpi_check_constraints();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff816b9ed0)
Location: drivers/acpi/x86/s2idle.c:288
Inline: False
```
**Symbols:**

```
ffffffff816b9ed0-ffffffff816ba04a: lpi_check_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void lpi_check_constraints();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff8169bdd0)
Location: drivers/acpi/x86/s2idle.c:290
Inline: False
```
**Symbols:**

```
ffffffff8169bdd0-ffffffff8169bf4a: lpi_check_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void lpi_check_constraints();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81711e50)
Location: drivers/acpi/x86/s2idle.c:290
Inline: False
```
**Symbols:**

```
ffffffff81711e50-ffffffff81711fca: lpi_check_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void lpi_check_constraints();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81841180)
Location: drivers/acpi/x86/s2idle.c:292
Inline: False
```
**Symbols:**

```
ffffffff81841180-ffffffff818412e4: lpi_check_constraints (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void lpi_check_constraints();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/x86/s2idle.c (ffffffff81977c10)
Location: drivers/acpi/x86/s2idle.c:293
Inline: False
```
**Symbols:**

```
ffffffff81977c10-ffffffff81977d6e: lpi_check_constraints (STB_LOCAL)
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
In drivers/acpi/x86/s2idle.c (ffffffff819bebda)
Location: drivers/acpi/x86/s2idle.c:287
Inline: True
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
In drivers/acpi/x86/s2idle.c (ffffffff81a093d6)
Location: drivers/acpi/x86/s2idle.c:326
Inline: True
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
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b5663)
Location: drivers/acpi/sleep.c:846
Inline: True
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
In drivers/acpi/sleep.c (ffffffff815cd453)
Location: drivers/acpi/sleep.c:846
Inline: True
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
In drivers/acpi/sleep.c (ffffffff815e72f3)
Location: drivers/acpi/sleep.c:846
Inline: True
```
</details>
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
</ul>
