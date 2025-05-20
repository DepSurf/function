# Function: <code>acpi_cppc_processor_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: include/acpi/processor.h:322
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: include/acpi/processor.h:342
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81525153)
Location: drivers/acpi/cppc_acpi.c:824
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff81525153-ffffffff815251bd: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81537a40)
Location: drivers/acpi/cppc_acpi.c:829
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff81537a40-ffffffff81537aaf: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81599240)
Location: drivers/acpi/cppc_acpi.c:869
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff81599240-ffffffff81599307: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815d0aa0)
Location: drivers/acpi/cppc_acpi.c:898
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff815d0aa0-ffffffff815d0b65: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815ea0d0)
Location: drivers/acpi/cppc_acpi.c:898
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff815ea0d0-ffffffff815ea195: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8161be30)
Location: drivers/acpi/cppc_acpi.c:894
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff8161be30-ffffffff8161bf0e: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8163d8d0)
Location: drivers/acpi/cppc_acpi.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff8163d8d0-ffffffff8163d9ae: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816eaca0)
Location: drivers/acpi/cppc_acpi.c:878
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff816eaca0-ffffffff816ead6e: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81708400)
Location: drivers/acpi/cppc_acpi.c:864
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff81708400-ffffffff817084ce: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816e9a00)
Location: drivers/acpi/cppc_acpi.c:856
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff816e9a00-ffffffff816e9ace: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:856
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff81cf1f0b-ffffffff81cf1f20: acpi_cppc_processor_exit.cold (STB_LOCAL)
ffffffff817630e0-ffffffff8176330d: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:906
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff81eb9ecf-ffffffff81eb9ee4: acpi_cppc_processor_exit.cold (STB_LOCAL)
ffffffff81897020-ffffffff8189725f: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:909
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff82092873-ffffffff82092888: acpi_cppc_processor_exit.cold (STB_LOCAL)
ffffffff819ded50-ffffffff819def8f: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:910
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff821135f5-ffffffff8211360a: acpi_cppc_processor_exit.cold (STB_LOCAL)
ffffffff81a26a60-ffffffff81a26c9f: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:913
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff821f0f68-ffffffff821f0f7d: acpi_cppc_processor_exit.cold (STB_LOCAL)
ffffffff81a71a70-ffffffff81a71caf: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffff8000107a8700)
Location: drivers/acpi/cppc_acpi.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffff8000107a8700-ffff8000107a880c: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
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
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81609300)
Location: drivers/acpi/cppc_acpi.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff81609300-ffffffff816093de: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815faf40)
Location: drivers/acpi/cppc_acpi.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff815faf40-ffffffff815fb01e: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81631710)
Location: drivers/acpi/cppc_acpi.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff81631710-ffffffff816317ee: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_cppc_processor_exit(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8164ba50)
Location: drivers/acpi/cppc_acpi.c:896
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_processor_stop
```
**Symbols:**

```
ffffffff8164ba50-ffffffff8164bb2e: acpi_cppc_processor_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
