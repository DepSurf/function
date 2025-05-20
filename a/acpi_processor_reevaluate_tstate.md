# Function: <code>acpi_processor_reevaluate_tstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814adf29)
Location: drivers/acpi/processor_throttling.c:377
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_cpu_soft_notify
  - drivers/acpi/processor_driver.c:acpi_cpu_soft_notify
```
**Symbols:**

```
ffffffff814adf29-ffffffff814adf74: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, long unsigned int action);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814fd8f7)
Location: drivers/acpi/processor_throttling.c:377
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_cpu_soft_notify
  - drivers/acpi/processor_driver.c:acpi_cpu_soft_notify
```
**Symbols:**

```
ffffffff814fd8f7-ffffffff814fd942: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815205f1)
Location: drivers/acpi/processor_throttling.c:377
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff815205f1-ffffffff8152063b: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81531de0)
Location: drivers/acpi/processor_throttling.c:377
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81531de0-ffffffff81531e2e: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81593140)
Location: drivers/acpi/processor_throttling.c:377
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81593140-ffffffff8159318e: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815ca530)
Location: drivers/acpi/processor_throttling.c:377
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff815ca530-ffffffff815ca57e: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815e3b10)
Location: drivers/acpi/processor_throttling.c:377
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff815e3b10-ffffffff815e3b5e: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816156e0)
Location: drivers/acpi/processor_throttling.c:364
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff816156e0-ffffffff8161572e: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81636bd0)
Location: drivers/acpi/processor_throttling.c:364
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81636bd0-ffffffff81636c1e: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e3de0)
Location: drivers/acpi/processor_throttling.c:364
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff816e3de0-ffffffff816e3e31: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81701a30)
Location: drivers/acpi/processor_throttling.c:363
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81701a30-ffffffff81701a81: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff816e3280)
Location: drivers/acpi/processor_throttling.c:359
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff816e3280-ffffffff816e32d1: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8175bcd0)
Location: drivers/acpi/processor_throttling.c:355
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff8175bcd0-ffffffff8175bd21: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8188f340)
Location: drivers/acpi/processor_throttling.c:355
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff8188f340-ffffffff8188f39f: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff819d6fe0)
Location: drivers/acpi/processor_throttling.c:353
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff819d6fe0-ffffffff819d703f: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a1e9a0)
Location: drivers/acpi/processor_throttling.c:353
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81a1e9a0-ffffffff81a1e9ff: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81a69cc0)
Location: drivers/acpi/processor_throttling.c:353
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81a69cc0-ffffffff81a69d1f: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_driver.c (0)
Location: include/acpi/processor.h:395
Inline: True
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
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81606060)
Location: drivers/acpi/processor_throttling.c:364
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81606060-ffffffff816060ae: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815f1130)
Location: drivers/acpi/processor_throttling.c:364
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff815f1130-ffffffff815f117e: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff8162aeb0)
Location: drivers/acpi/processor_throttling.c:364
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff8162aeb0-ffffffff8162aefe: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_processor_reevaluate_tstate(struct acpi_processor *pr, bool is_dead);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81644d50)
Location: drivers/acpi/processor_throttling.c:364
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_dead
  - drivers/acpi/processor_driver.c:acpi_soft_cpu_online
```
**Symbols:**

```
ffffffff81644d50-ffffffff81644d9e: acpi_processor_reevaluate_tstate (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool is_dead</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int action</code>
</li>
</ul>
</details>
</li>
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
