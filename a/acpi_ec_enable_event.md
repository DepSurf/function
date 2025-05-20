# Function: <code>acpi_ec_enable_event</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f538b)
Location: drivers/acpi/ec.c:515
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff814f538b-ffffffff814f5465: acpi_ec_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81502bd0)
Location: drivers/acpi/ec.c:500
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81502bd0-ffffffff81502c4e: acpi_ec_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81545030)
Location: drivers/acpi/ec.c:502
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81545030-ffffffff815450a4: acpi_ec_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:502
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff8157b090-ffffffff8157b0eb: acpi_ec_enable_event (STB_LOCAL)
ffffffff8157c43f-ffffffff8157c450: acpi_ec_enable_event.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:502
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81592d10-ffffffff81592d6b: acpi_ec_enable_event (STB_LOCAL)
ffffffff8159411f-ffffffff81594130: acpi_ec_enable_event.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:512
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815c49a0-ffffffff815c4a66: acpi_ec_enable_event (STB_LOCAL)
ffffffff815c516f-ffffffff815c51aa: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:514
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815e5be0-ffffffff815e5ca6: acpi_ec_enable_event (STB_LOCAL)
ffffffff815e639d-ffffffff815e63d8: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:520
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81690ea0-ffffffff81690f68: acpi_ec_enable_event (STB_LOCAL)
ffffffff81691a24-ffffffff81691a5f: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:503
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff816aebd0-ffffffff816aec9a: acpi_ec_enable_event (STB_LOCAL)
ffffffff81c01665-ffffffff81c016a0: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:504
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff816911e0-ffffffff816912aa: acpi_ec_enable_event (STB_LOCAL)
ffffffff81bf2efe-ffffffff81bf2f39: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:506
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81706c90-ffffffff81706d5a: acpi_ec_enable_event (STB_LOCAL)
ffffffff81cefa55-ffffffff81cefa90: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:525
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81834e10-ffffffff81834ea5: acpi_ec_enable_event (STB_LOCAL)
ffffffff81eb75cb-ffffffff81eb7605: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819689f0)
Location: drivers/acpi/ec.c:526
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff819689f0-ffffffff81968ab3: acpi_ec_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819aefd0)
Location: drivers/acpi/ec.c:526
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff819aefd0-ffffffff819af093: acpi_ec_enable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819f9480)
Location: drivers/acpi/ec.c:526
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff819f9480-ffffffff819f9543: acpi_ec_enable_event (STB_LOCAL)
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
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff8000107729b8)
Location: drivers/acpi/ec.c:514
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffff8000107729b8-ffff800010772b40: acpi_ec_enable_event (STB_LOCAL)
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
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:514
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815d7ad0-ffffffff815d7b96: acpi_ec_enable_event (STB_LOCAL)
ffffffff815d825d-ffffffff815d8298: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:514
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815c1690-ffffffff815c1756: acpi_ec_enable_event (STB_LOCAL)
ffffffff815c1e4d-ffffffff815c1e88: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:514
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815d9ec0-ffffffff815d9f86: acpi_ec_enable_event (STB_LOCAL)
ffffffff815da67d-ffffffff815da6b8: acpi_ec_enable_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_ec_enable_event(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:514
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_resume
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815f3d80-ffffffff815f3e46: acpi_ec_enable_event (STB_LOCAL)
ffffffff815f453d-ffffffff815f4578: acpi_ec_enable_event.cold (STB_LOCAL)
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
