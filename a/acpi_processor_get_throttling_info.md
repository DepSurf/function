# Function: <code>acpi_processor_get_throttling_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814ae0e6)
Location: drivers/acpi/processor_throttling.c:1176
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff814ae0e6-ffffffff814ae61a: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff814fdab0)
Location: drivers/acpi/processor_throttling.c:1185
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff814fdab0-ffffffff814fdfe3: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815207a9)
Location: drivers/acpi/processor_throttling.c:1185
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815207a9-ffffffff81520cdc: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff81531e50)
Location: drivers/acpi/processor_throttling.c:1195
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81531e50-ffffffff815324f8: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_throttling.c (ffffffff815931b0)
Location: drivers/acpi/processor_throttling.c:1195
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815931b0-ffffffff81593aae: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1196
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815cadd7-ffffffff815caf14: acpi_processor_get_throttling_info.cold.9 (STB_LOCAL)
ffffffff815ca5a0-ffffffff815cad91: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1196
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815e43b7-ffffffff815e44f4: acpi_processor_get_throttling_info.cold.10 (STB_LOCAL)
ffffffff815e3b80-ffffffff815e4371: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1183
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81615f93-ffffffff816160d0: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff81615750-ffffffff81615f12: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1183
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81637483-ffffffff816375c0: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff81636c40-ffffffff81637402: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1176
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
```
**Symbols:**

```
ffffffff816e4305-ffffffff816e4318: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff816e3e60-ffffffff816e418e: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1175
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:acpi_pss_perf_init
```
**Symbols:**

```
ffffffff81c02c90-ffffffff81c02ca3: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff81701ab0-ffffffff81701dde: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1171
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81bf466a-ffffffff81bf46e6: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff816e3300-ffffffff816e36b8: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1161
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81cf1757-ffffffff81cf17f3: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff8175bd50-ffffffff8175c15e: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1161
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81eb9717-ffffffff81eb9748: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff8188f3d0-ffffffff8188f6ca: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1159
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff820927d7-ffffffff820927f7: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff819d7090-ffffffff819d73a4: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1159
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff82113121-ffffffff82113144: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff81a1ea50-ffffffff81a1ed64: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1159
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff821f0e75-ffffffff821f0e98: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff81a69d70-ffffffff81a6a084: acpi_processor_get_throttling_info (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1183
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff816066ac-ffffffff816067e9: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff816060d0-ffffffff81606634: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1183
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff815f177c-ffffffff815f18b9: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff815f11a0-ffffffff815f1704: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1183
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff8162b763-ffffffff8162b8a0: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff8162af20-ffffffff8162b6e2: acpi_processor_get_throttling_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_throttling_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_throttling.c (0)
Location: drivers/acpi/processor_throttling.c:1183
Inline: False
Direct callers:
  - drivers/acpi/processor_driver.c:__acpi_processor_start
```
**Symbols:**

```
ffffffff81645603-ffffffff81645740: acpi_processor_get_throttling_info.cold (STB_LOCAL)
ffffffff81644dc0-ffffffff81645582: acpi_processor_get_throttling_info (STB_GLOBAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
