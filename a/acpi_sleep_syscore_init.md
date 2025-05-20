# Function: <code>acpi_sleep_syscore_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_sleep_syscore_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ca37a)
Location: drivers/acpi/sleep.c:728
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff814ca37a-ffffffff814ca391: acpi_sleep_syscore_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_sleep_syscore_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff814ec296)
Location: drivers/acpi/sleep.c:711
Inline: False
Direct callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff814ec296-ffffffff814ec2ad: acpi_sleep_syscore_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_sleep_syscore_init();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff820ebbdb)
Location: drivers/acpi/sleep.c:873
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
**Symbols:**

```
ffffffff814f8a40-ffffffff814f8a57: acpi_sleep_syscore_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff826f4aba)
Location: drivers/acpi/sleep.c:1075
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff8271ead8)
Location: drivers/acpi/sleep.c:1107
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff828d6b03)
Location: drivers/acpi/sleep.c:1113
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff828f097a)
Location: drivers/acpi/sleep.c:1107
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff828f9ae4)
Location: drivers/acpi/sleep.c:1148
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff82d10c07)
Location: drivers/acpi/sleep.c:1146
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff82ffe6ed)
Location: drivers/acpi/sleep.c:865
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff832094a0)
Location: drivers/acpi/sleep.c:865
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff832f1783)
Location: drivers/acpi/sleep.c:866
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff834a9835)
Location: drivers/acpi/sleep.c:883
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff83ee13ed)
Location: drivers/acpi/sleep.c:890
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff83706dad)
Location: drivers/acpi/sleep.c:904
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff8393a32d)
Location: drivers/acpi/sleep.c:904
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff828e2822)
Location: drivers/acpi/sleep.c:1148
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/sleep.c (ffffffff828da83b)
Location: drivers/acpi/sleep.c:1148
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff828f56e0)
Location: drivers/acpi/sleep.c:1148
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
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
In drivers/acpi/sleep.c (ffffffff828fab38)
Location: drivers/acpi/sleep.c:1148
Inline: True
Inline callers:
  - drivers/acpi/sleep.c:acpi_sleep_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
