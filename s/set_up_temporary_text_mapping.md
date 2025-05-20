# Function: <code>set_up_temporary_text_mapping</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff817605f7)
Location: arch/x86/power/hibernate_64.c:44
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff8178d757)
Location: arch/x86/power/hibernate_64.c:48
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff817ab8ef)
Location: arch/x86/power/hibernate_64.c:49
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff81822e67)
Location: arch/x86/power/hibernate_64.c:49
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff8186d16c)
Location: arch/x86/power/hibernate_64.c:49
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff8188d01c)
Location: arch/x86/power/hibernate_64.c:29
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff818d7a4c)
Location: arch/x86/power/hibernate_64.c:28
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff81909d8c)
Location: arch/x86/power/hibernate_64.c:28
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_up_temporary_text_mapping(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff81bba620)
Location: arch/x86/power/hibernate_64.c:28
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_mappings
```
**Symbols:**

```
ffffffff81bba620-ffffffff81bba8b1: set_up_temporary_text_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_up_temporary_text_mapping(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff81bced50)
Location: arch/x86/power/hibernate_64.c:28
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:set_up_temporary_mappings
```
**Symbols:**

```
ffffffff81bced50-ffffffff81bcefe1: set_up_temporary_text_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_up_temporary_text_mapping(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/power/hibernate_64.c (ffffffff81bc2700)
Location: arch/x86/power/hibernate_64.c:28
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81bc2700-ffffffff81bc29ac: set_up_temporary_text_mapping (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int set_up_temporary_text_mapping(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/power/hibernate_64.c:28
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81c92dc0-ffffffff81c93067: set_up_temporary_text_mapping (STB_LOCAL)
ffffffff81d44fca-ffffffff81d4503a: set_up_temporary_text_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int set_up_temporary_text_mapping(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/power/hibernate_64.c:28
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81e42760-ffffffff81e42a15: set_up_temporary_text_mapping (STB_LOCAL)
ffffffff81f11ea3-ffffffff81f11f13: set_up_temporary_text_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int set_up_temporary_text_mapping(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/power/hibernate_64.c:28
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8201d190-ffffffff8201d478: set_up_temporary_text_mapping (STB_LOCAL)
ffffffff820b7398-ffffffff820b7408: set_up_temporary_text_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int set_up_temporary_text_mapping(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/power/hibernate_64.c:28
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8209d820-ffffffff8209db08: set_up_temporary_text_mapping (STB_LOCAL)
ffffffff82138720-ffffffff82138790: set_up_temporary_text_mapping.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int set_up_temporary_text_mapping(pgd_t *pgd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/power/hibernate_64.c (0)
Location: arch/x86/power/hibernate_64.c:28
Inline: False
Direct callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff82175020-ffffffff82175308: set_up_temporary_text_mapping (STB_LOCAL)
ffffffff8221a6ba-ffffffff8221a72a: set_up_temporary_text_mapping.cold (STB_LOCAL)
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
In arch/x86/power/hibernate_64.c (ffffffff818a914c)
Location: arch/x86/power/hibernate_64.c:28
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff81863dbf)
Location: arch/x86/power/hibernate_64.c:28
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff818fa7ac)
Location: arch/x86/power/hibernate_64.c:28
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
In arch/x86/power/hibernate_64.c (ffffffff8191b90c)
Location: arch/x86/power/hibernate_64.c:28
Inline: True
Inline callers:
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
