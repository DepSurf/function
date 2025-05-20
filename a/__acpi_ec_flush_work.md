# Function: <code>__acpi_ec_flush_work</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e3930)
Location: drivers/acpi/ec.c:529
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
**Symbols:**

```
ffffffff815e3930-ffffffff815e3953: __acpi_ec_flush_work (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff816918c2)
Location: drivers/acpi/ec.c:535
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/acpi/ec.c (ffffffff816af5e7)
Location: drivers/acpi/ec.c:518
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/acpi/ec.c (ffffffff81691bf7)
Location: drivers/acpi/ec.c:519
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
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
In drivers/acpi/ec.c (ffffffff817076c0)
Location: drivers/acpi/ec.c:521
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81832cb0)
Location: drivers/acpi/ec.c:540
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
```
**Symbols:**

```
ffffffff81832cb0-ffffffff81832cd9: __acpi_ec_flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81966610)
Location: drivers/acpi/ec.c:541
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
```
**Symbols:**

```
ffffffff81966610-ffffffff81966639: __acpi_ec_flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819acba0)
Location: drivers/acpi/ec.c:541
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
```
**Symbols:**

```
ffffffff819acba0-ffffffff819acbc9: __acpi_ec_flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff819f6fc0)
Location: drivers/acpi/ec.c:541
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_dispatch_gpe
  - drivers/acpi/ec.c:acpi_ec_suspend
```
**Symbols:**

```
ffffffff819f6fc0-ffffffff819f6fe9: __acpi_ec_flush_work (STB_LOCAL)
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
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff80001076fdd8)
Location: drivers/acpi/ec.c:529
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
**Symbols:**

```
ffff80001076fdd8-ffff80001076fe10: __acpi_ec_flush_work (STB_LOCAL)
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
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d5820)
Location: drivers/acpi/ec.c:529
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
**Symbols:**

```
ffffffff815d5820-ffffffff815d5843: __acpi_ec_flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815bf3e0)
Location: drivers/acpi/ec.c:529
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
**Symbols:**

```
ffffffff815bf3e0-ffffffff815bf403: __acpi_ec_flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d7c10)
Location: drivers/acpi/ec.c:529
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
**Symbols:**

```
ffffffff815d7c10-ffffffff815d7c33: __acpi_ec_flush_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __acpi_ec_flush_work();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f1ad0)
Location: drivers/acpi/ec.c:529
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_suspend
  - drivers/acpi/ec.c:acpi_ec_flush_work
```
**Symbols:**

```
ffffffff815f1ad0-ffffffff815f1af3: __acpi_ec_flush_work (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
