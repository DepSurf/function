# Function: <code>acpi_ec_enter_noirq</code>

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
In drivers/acpi/ec.c (ffffffff814f3c13)
Location: drivers/acpi/ec.c:1842
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
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
In drivers/acpi/ec.c (ffffffff815039c7)
Location: drivers/acpi/ec.c:990
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
In drivers/acpi/ec.c (ffffffff81545e31)
Location: drivers/acpi/ec.c:992
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
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81579dc0)
Location: drivers/acpi/ec.c:992
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81579dc0-ffffffff81579e12: acpi_ec_enter_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81591a40)
Location: drivers/acpi/ec.c:992
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff81591a40-ffffffff81591a92: acpi_ec_enter_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c2910)
Location: drivers/acpi/ec.c:1006
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815c2910-ffffffff815c2962: acpi_ec_enter_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e3c20)
Location: drivers/acpi/ec.c:998
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815e3c20-ffffffff815e3c72: acpi_ec_enter_noirq (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff8168f641)
Location: drivers/acpi/ec.c:994
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
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
In drivers/acpi/ec.c (ffffffff816ad311)
Location: drivers/acpi/ec.c:981
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
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
In drivers/acpi/ec.c (ffffffff8168f931)
Location: drivers/acpi/ec.c:982
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
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
In drivers/acpi/ec.c (ffffffff81705400)
Location: drivers/acpi/ec.c:984
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
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
In drivers/acpi/ec.c (ffffffff818336e0)
Location: drivers/acpi/ec.c:1007
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
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
In drivers/acpi/ec.c (ffffffff81967470)
Location: drivers/acpi/ec.c:1004
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
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
In drivers/acpi/ec.c (ffffffff819ada40)
Location: drivers/acpi/ec.c:989
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
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
In drivers/acpi/ec.c (ffffffff819f7ec0)
Location: drivers/acpi/ec.c:989
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
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
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010770ba8)
Location: drivers/acpi/ec.c:998
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffff800010770ba8-ffff800010770c58: acpi_ec_enter_noirq (STB_LOCAL)
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
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d5b10)
Location: drivers/acpi/ec.c:998
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815d5b10-ffffffff815d5b62: acpi_ec_enter_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815bf6d0)
Location: drivers/acpi/ec.c:998
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815bf6d0-ffffffff815bf722: acpi_ec_enter_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d7f00)
Location: drivers/acpi/ec.c:998
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815d7f00-ffffffff815d7f52: acpi_ec_enter_noirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ec_enter_noirq(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f1dc0)
Location: drivers/acpi/ec.c:998
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend_noirq
  - drivers/acpi/ec.c:ec_install_handlers
```
**Symbols:**

```
ffffffff815f1dc0-ffffffff815f1e12: acpi_ec_enter_noirq (STB_LOCAL)
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
