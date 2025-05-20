# Function: <code>acpi_lpss_resume</code>

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
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8154a200)
Location: drivers/acpi/acpi_lpss.c:825
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff8154a200-ffffffff8154a35b: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81580410)
Location: drivers/acpi/acpi_lpss.c:982
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff81580410-ffffffff8158057d: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81598320)
Location: drivers/acpi/acpi_lpss.c:1015
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff81598320-ffffffff8159848d: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c94b0)
Location: drivers/acpi/acpi_lpss.c:1012
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff815c94b0-ffffffff815c9614: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815ea6d0)
Location: drivers/acpi/acpi_lpss.c:1037
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff815ea6d0-ffffffff815ea834: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81696570)
Location: drivers/acpi/acpi_lpss.c:1015
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff81696570-ffffffff816966cf: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816b36c0)
Location: drivers/acpi/acpi_lpss.c:1027
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff816b36c0-ffffffff816b381f: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81695940)
Location: drivers/acpi/acpi_lpss.c:1028
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff81695940-ffffffff81695a9f: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (0)
Location: drivers/acpi/acpi_lpss.c:1029
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
```
**Symbols:**

```
ffffffff8170b670-ffffffff8170b7db: acpi_lpss_resume (STB_LOCAL)
ffffffff81cf06aa-ffffffff81cf06be: acpi_lpss_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (0)
Location: drivers/acpi/acpi_lpss.c:1051
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff81839be0-ffffffff81839d71: acpi_lpss_resume (STB_LOCAL)
ffffffff81eb8525-ffffffff81eb8539: acpi_lpss_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (0)
Location: drivers/acpi/acpi_lpss.c:1040
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff8196f200-ffffffff8196f391: acpi_lpss_resume (STB_LOCAL)
ffffffff82091bfd-ffffffff82091c11: acpi_lpss_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (0)
Location: drivers/acpi/acpi_lpss.c:1055
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff819b5780-ffffffff819b5946: acpi_lpss_resume (STB_LOCAL)
ffffffff821124c5-ffffffff821124d9: acpi_lpss_resume.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (0)
Location: drivers/acpi/acpi_lpss.c:1019
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff819ffb80-ffffffff819ffd46: acpi_lpss_resume (STB_LOCAL)
ffffffff821f022d-ffffffff821f0241: acpi_lpss_resume.cold (STB_LOCAL)
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
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c5140)
Location: drivers/acpi/acpi_lpss.c:1037
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff815c5140-ffffffff815c52a4: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815de9b0)
Location: drivers/acpi/acpi_lpss.c:1037
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff815de9b0-ffffffff815deb14: acpi_lpss_resume (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_lpss_resume(struct device *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815f8870)
Location: drivers/acpi/acpi_lpss.c:1037
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_restore_early
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_noirq
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume_early
```
**Symbols:**

```
ffffffff815f8870-ffffffff815f89d4: acpi_lpss_resume (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
