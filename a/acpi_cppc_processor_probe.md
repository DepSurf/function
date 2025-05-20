# Function: <code>acpi_cppc_processor_probe</code>

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
Location: include/acpi/processor.h:318
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
Location: include/acpi/processor.h:338
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815257af)
Location: drivers/acpi/cppc_acpi.c:650
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815257af-ffffffff81525d71: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815381e0)
Location: drivers/acpi/cppc_acpi.c:655
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815381e0-ffffffff81538913: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815999f0)
Location: drivers/acpi/cppc_acpi.c:691
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815999f0-ffffffff8159a19b: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:718
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815d2af1-ffffffff815d2b4b: acpi_cppc_processor_probe.cold.4 (STB_LOCAL)
ffffffff815d1250-ffffffff815d1a99: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:718
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815ec2a1-ffffffff815ec2fb: acpi_cppc_processor_probe.cold.5 (STB_LOCAL)
ffffffff815ea880-ffffffff815eb0b9: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:714
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff8161e071-ffffffff8161e0cb: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff8161c600-ffffffff8161ce57: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:716
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff8163fb21-ffffffff8163fb7b: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff8163e0a0-ffffffff8163e904: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:697
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff816ecb79-ffffffff816ecbd3: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff816eb3a0-ffffffff816eba2b: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:681
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81c032ad-ffffffff81c03307: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff817089f0-ffffffff8170908a: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:673
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81bf4c9f-ffffffff81bf4cf9: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff816ea010-ffffffff816ea6a9: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:673
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81cf1f7c-ffffffff81cf1feb: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff81763930-ffffffff81764431: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:660
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81eb9f4e-ffffffff81eba029: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff81897720-ffffffff818984e8: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:663
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff820928cd-ffffffff82092974: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff819dfa10-ffffffff819e0810: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:664
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff8211364f-ffffffff821136f6: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff81a27720-ffffffff81a285ad: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:667
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff821f0fc2-ffffffff821f1069: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff81a72890-ffffffff81a7377b: acpi_cppc_processor_probe (STB_GLOBAL)
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
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffff8000107a9078)
Location: drivers/acpi/cppc_acpi.c:716
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffff8000107a9078-ffff8000107a994c: acpi_cppc_processor_probe (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:716
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff8160b551-ffffffff8160b5ab: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff81609ad0-ffffffff8160a334: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:716
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815fd191-ffffffff815fd1eb: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff815fb710-ffffffff815fbf74: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:716
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81633961-ffffffff816339bb: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff81631ee0-ffffffff81632744: acpi_cppc_processor_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_cppc_processor_probe(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:716
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff8164dc8d-ffffffff8164dce7: acpi_cppc_processor_probe.cold (STB_LOCAL)
ffffffff8164c210-ffffffff8164ca74: acpi_cppc_processor_probe (STB_GLOBAL)
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
