# Function: <code>ghes_edac_report_mem_error</code>

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
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:59
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
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:59
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:59
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/apei/ghes.c (0)
Location: include/acpi/ghes.h:65
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(struct ghes *ghes, int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff817d2990)
Location: drivers/edac/ghes_edac.c:175
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_do_proc
```
**Symbols:**

```
ffffffff817d2990-ffffffff817d385a: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff8181b770)
Location: drivers/edac/ghes_edac.c:184
Inline: False
```
**Symbols:**

```
ffffffff8181b770-ffffffff8181c63b: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81846fa0)
Location: drivers/edac/ghes_edac.c:198
Inline: False
```
**Symbols:**

```
ffffffff81846fa0-ffffffff81847fb0: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81889d60)
Location: drivers/edac/ghes_edac.c:196
Inline: False
```
**Symbols:**

```
ffffffff81889d60-ffffffff8188ae2f: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff818bbd10)
Location: drivers/edac/ghes_edac.c:204
Inline: False
```
**Symbols:**

```
ffffffff818bbd10-ffffffff818bce08: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff8198c5c0)
Location: drivers/edac/ghes_edac.c:202
Inline: False
```
**Symbols:**

```
ffffffff8198c5c0-ffffffff8198d452: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:238
Inline: False
```
**Symbols:**

```
ffffffff81c28d60-ffffffff81c28d78: ghes_edac_report_mem_error.cold (STB_LOCAL)
ffffffff81990020-ffffffff81991021: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:238
Inline: False
```
**Symbols:**

```
ffffffff81c1af4c-ffffffff81c1af64: ghes_edac_report_mem_error.cold (STB_LOCAL)
ffffffff819745a0-ffffffff81975594: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:238
Inline: False
```
**Symbols:**

```
ffffffff81d2ae7c-ffffffff81d2ae94: ghes_edac_report_mem_error.cold (STB_LOCAL)
ffffffff81a1d2a0-ffffffff81a1e291: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/edac/ghes_edac.c (0)
Location: drivers/edac/ghes_edac.c:270
Inline: False
```
**Symbols:**

```
ffffffff81ef7015-ffffffff81ef702d: ghes_edac_report_mem_error.cold (STB_LOCAL)
ffffffff81b86540-ffffffff81b869cd: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ghes_edac_report_mem_error(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81d25de0)
Location: drivers/edac/ghes_edac.c:269
Inline: False
```
**Symbols:**

```
ffffffff81d25de0-ffffffff81d26286: ghes_edac_report_mem_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ghes_edac_report_mem_error(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81d8f010)
Location: drivers/edac/ghes_edac.c:269
Inline: False
```
**Symbols:**

```
ffffffff81d8f010-ffffffff81d8f4b6: ghes_edac_report_mem_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ghes_edac_report_mem_error(struct notifier_block *nb, long unsigned int val, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff81e46920)
Location: drivers/edac/ghes_edac.c:269
Inline: False
```
**Symbols:**

```
ffffffff81e46920-ffffffff81e46dc6: ghes_edac_report_mem_error (STB_LOCAL)
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
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffff800010b146e8)
Location: drivers/edac/ghes_edac.c:204
Inline: False
```
**Symbols:**

```
ffff800010b146e8-ffff800010b1527c: ghes_edac_report_mem_error (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff818b11c0)
Location: drivers/edac/ghes_edac.c:204
Inline: False
```
**Symbols:**

```
ffffffff818b11c0-ffffffff818b22b8: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ghes_edac_report_mem_error(int sev, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/ghes_edac.c (ffffffff818cd450)
Location: drivers/edac/ghes_edac.c:204
Inline: False
```
**Symbols:**

```
ffffffff818cd450-ffffffff818ce561: ghes_edac_report_mem_error (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ghes *ghes</code>
</li>
<li>
<b>Param reordered. </b>
<code>ghes, sev, mem_err</code> ➡️ <code>sev, mem_err</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct notifier_block *nb</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int val</code>
</li>
<li>
<b>Param added. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>int sev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct cper_sec_mem_err *mem_err</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
