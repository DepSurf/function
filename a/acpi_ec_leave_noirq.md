# Function: <code>acpi_ec_leave_noirq</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f3bae)
Location: drivers/acpi/ec.c:1857
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
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
In drivers/acpi/ec.c (ffffffff81503a62)
Location: drivers/acpi/ec.c:1001
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffffffff81545eda)
Location: drivers/acpi/ec.c:1003
Inline: True
Inline callers:
  - drivers/acpi/ec.c:ec_install_handlers
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81579e20)
Location: drivers/acpi/ec.c:1003
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81579e20-ffffffff81579e7a: acpi_ec_leave_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81591aa0)
Location: drivers/acpi/ec.c:1003
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81591aa0-ffffffff81591afa: acpi_ec_leave_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c2970)
Location: drivers/acpi/ec.c:1017
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815c2970-ffffffff815c29ca: acpi_ec_leave_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e3cd0)
Location: drivers/acpi/ec.c:1009
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815e3cd0-ffffffff815e3d2a: acpi_ec_leave_noirq (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff8168f8c2)
Location: drivers/acpi/ec.c:1005
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffffffff816ad592)
Location: drivers/acpi/ec.c:992
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffffffff8168fb12)
Location: drivers/acpi/ec.c:993
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffffffff81705794)
Location: drivers/acpi/ec.c:995
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffffffff81833b64)
Location: drivers/acpi/ec.c:1018
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffffffff81967814)
Location: drivers/acpi/ec.c:1015
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffffffff819adde4)
Location: drivers/acpi/ec.c:1000
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffffffff819f8264)
Location: drivers/acpi/ec.c:1000
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
In drivers/acpi/ec.c (ffff800010770a48)
Location: drivers/acpi/ec.c:1009
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
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
void acpi_ec_leave_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d5bc0)
Location: drivers/acpi/ec.c:1009
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815d5bc0-ffffffff815d5c1a: acpi_ec_leave_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815bf780)
Location: drivers/acpi/ec.c:1009
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815bf780-ffffffff815bf7da: acpi_ec_leave_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d7fb0)
Location: drivers/acpi/ec.c:1009
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815d7fb0-ffffffff815d800a: acpi_ec_leave_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ec_leave_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f1e70)
Location: drivers/acpi/ec.c:1009
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815f1e70-ffffffff815f1eca: acpi_ec_leave_noirq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
