# Function: <code>acpi_s2idle_setup</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_s2idle_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816a1c50)
Location: drivers/acpi/sleep.c:811
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff816ba950-ffffffff816ba973: acpi_s2idle_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_s2idle_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81684a40)
Location: drivers/acpi/sleep.c:811
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff8169c880-ffffffff8169c8a3: acpi_s2idle_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_s2idle_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff816f9d00)
Location: drivers/acpi/sleep.c:812
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff81712c00-ffffffff81712c23: acpi_s2idle_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_s2idle_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81827040)
Location: drivers/acpi/sleep.c:825
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff81842160-ffffffff8184218b: acpi_s2idle_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_s2idle_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff81958ed0)
Location: drivers/acpi/sleep.c:829
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff83ee3470-ffffffff83ee34a7: acpi_s2idle_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_s2idle_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff8199f340)
Location: drivers/acpi/sleep.c:843
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff83708e80-ffffffff83708eab: acpi_s2idle_setup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_s2idle_setup();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff819e79e0)
Location: drivers/acpi/sleep.c:843
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff8393c2c0-ffffffff8393c2eb: acpi_s2idle_setup (STB_GLOBAL)
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
