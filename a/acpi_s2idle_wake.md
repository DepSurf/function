# Function: <code>acpi_s2idle_wake</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815394d0)
Location: drivers/acpi/sleep.c:959
Inline: False
```
**Symbols:**

```
ffffffff815394d0-ffffffff8153965d: acpi_s2idle_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8156f600)
Location: drivers/acpi/sleep.c:985
Inline: True
```
**Symbols:**

```
ffffffff8156f600-ffffffff8156f79a: acpi_s2idle_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815871e0)
Location: drivers/acpi/sleep.c:986
Inline: True
```
**Symbols:**

```
ffffffff815871e0-ffffffff8158737a: acpi_s2idle_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b7e50)
Location: drivers/acpi/sleep.c:978
Inline: True
```
**Symbols:**

```
ffffffff815b7e50-ffffffff815b7ff3: acpi_s2idle_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815d9050)
Location: drivers/acpi/sleep.c:990
Inline: True
```
**Symbols:**

```
ffffffff815d9050-ffffffff815d90de: acpi_s2idle_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816830c0)
Location: drivers/acpi/sleep.c:983
Inline: True
```
**Symbols:**

```
ffffffff816830c0-ffffffff816831af: acpi_s2idle_wake.part.0 (STB_LOCAL)
ffffffff816831b0-ffffffff816831d0: acpi_s2idle_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816a14b0)
Location: drivers/acpi/sleep.c:710
Inline: True
```
**Symbols:**

```
ffffffff816a14b0-ffffffff816a159f: acpi_s2idle_wake.part.0 (STB_LOCAL)
ffffffff816a15a0-ffffffff816a15c0: acpi_s2idle_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81684330)
Location: drivers/acpi/sleep.c:710
Inline: True
```
**Symbols:**

```
ffffffff81684330-ffffffff8168443c: acpi_s2idle_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816f95e0)
Location: drivers/acpi/sleep.c:710
Inline: True
```
**Symbols:**

```
ffffffff816f95e0-ffffffff816f9703: acpi_s2idle_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81826aa0)
Location: drivers/acpi/sleep.c:727
Inline: True
```
**Symbols:**

```
ffffffff818268a0-ffffffff81826a91: acpi_s2idle_wake.part.0 (STB_LOCAL)
ffffffff81eb6988-ffffffff81eb6a6b: acpi_s2idle_wake.part.0.cold (STB_LOCAL)
ffffffff81826aa0-ffffffff81826ac8: acpi_s2idle_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81958880)
Location: drivers/acpi/sleep.c:731
Inline: True
```
**Symbols:**

```
ffffffff81958620-ffffffff81958868: acpi_s2idle_wake.part.0 (STB_LOCAL)
ffffffff82091800-ffffffff8209187d: acpi_s2idle_wake.part.0.cold (STB_LOCAL)
ffffffff81958880-ffffffff819588a8: acpi_s2idle_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8199e910)
Location: drivers/acpi/sleep.c:745
Inline: True
```
**Symbols:**

```
ffffffff8199e910-ffffffff8199eaf3: acpi_s2idle_wake.part.0 (STB_LOCAL)
ffffffff8199eb10-ffffffff8199eb38: acpi_s2idle_wake (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff819e6fb0)
Location: drivers/acpi/sleep.c:745
Inline: True
```
**Symbols:**

```
ffffffff819e6fb0-ffffffff819e7193: acpi_s2idle_wake.part.0 (STB_LOCAL)
ffffffff819e71b0-ffffffff819e71d8: acpi_s2idle_wake (STB_GLOBAL)
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
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815b5540)
Location: drivers/acpi/sleep.c:990
Inline: True
```
**Symbols:**

```
ffffffff815b5540-ffffffff815b55ce: acpi_s2idle_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815cd330)
Location: drivers/acpi/sleep.c:990
Inline: True
```
**Symbols:**

```
ffffffff815cd330-ffffffff815cd3be: acpi_s2idle_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool acpi_s2idle_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff815e71d0)
Location: drivers/acpi/sleep.c:990
Inline: True
```
**Symbols:**

```
ffffffff815e71d0-ffffffff815e725e: acpi_s2idle_wake (STB_LOCAL)
```
</details>
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
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
