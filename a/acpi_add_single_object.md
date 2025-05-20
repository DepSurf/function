# Function: <code>acpi_add_single_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814809c3)
Location: drivers/acpi/scan.c:1413
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
```
**Symbols:**

```
ffffffff814809c3-ffffffff81480f1f: acpi_add_single_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cf366)
Location: drivers/acpi/scan.c:1433
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff814cf366-ffffffff814cf8c9: acpi_add_single_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f12d0)
Location: drivers/acpi/scan.c:1463
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff814f12d0-ffffffff814f1833: acpi_add_single_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fecb0)
Location: drivers/acpi/scan.c:1492
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff814fecb0-ffffffff814ff261: acpi_add_single_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81540cb0)
Location: drivers/acpi/scan.c:1591
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff81540cb0-ffffffff81541348: acpi_add_single_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1594
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff81576b70-ffffffff8157721d: acpi_add_single_object (STB_LOCAL)
ffffffff81577ca7-ffffffff81577cbe: acpi_add_single_object.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1607
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8158e760-ffffffff8158ee11: acpi_add_single_object (STB_LOCAL)
ffffffff8158f8e7-ffffffff8158f8fe: acpi_add_single_object.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1606
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815bf4c0-ffffffff815bfb7a: acpi_add_single_object (STB_LOCAL)
ffffffff815c0623-ffffffff815c063a: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1606
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815e0780-ffffffff815e0e3a: acpi_add_single_object (STB_LOCAL)
ffffffff815e18e3-ffffffff815e18fa: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1615
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8168bc10-ffffffff8168bdcb: acpi_add_single_object (STB_LOCAL)
ffffffff8168c64b-ffffffff8168c662: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1682
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff816a9a70-ffffffff816a9c9c: acpi_add_single_object (STB_LOCAL)
ffffffff81c011ee-ffffffff81c0120e: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, bool dep_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1702
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8168c2b0-ffffffff8168c560: acpi_add_single_object (STB_LOCAL)
ffffffff81bf2b77-ffffffff81bf2b8b: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, bool dep_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1784
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff81701a80-ffffffff81701d9b: acpi_add_single_object (STB_LOCAL)
ffffffff81cef53a-ffffffff81cef54e: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, bool dep_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1827
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff8182f710-ffffffff8182fa51: acpi_add_single_object (STB_LOCAL)
ffffffff81eb6f8e-ffffffff81eb6fb7: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, bool dep_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1811
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff81962790-ffffffff81962aeb: acpi_add_single_object (STB_LOCAL)
ffffffff8209196b-ffffffff82091980: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, bool dep_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1814
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff819a8b90-ffffffff819a8ef6: acpi_add_single_object (STB_LOCAL)
ffffffff82112276-ffffffff8211228b: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, bool dep_init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1826
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_scan_fixed
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff819f15a0-ffffffff819f1935: acpi_add_single_object (STB_LOCAL)
ffffffff821eff8e-ffffffff821effa3: acpi_add_single_object.cold (STB_LOCAL)
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
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076d088)
Location: drivers/acpi/scan.c:1606
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffff80001076d088-ffff80001076d668: acpi_add_single_object (STB_LOCAL)
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
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1606
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815d2b80-ffffffff815d316d: acpi_add_single_object (STB_LOCAL)
ffffffff815d3bb3-ffffffff815d3bca: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1606
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815bc740-ffffffff815bcd2d: acpi_add_single_object (STB_LOCAL)
ffffffff815bd773-ffffffff815bd78a: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1606
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815d4a60-ffffffff815d511a: acpi_add_single_object (STB_LOCAL)
ffffffff815d5bc3-ffffffff815d5bda: acpi_add_single_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_add_single_object(struct acpi_device **child, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1606
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_scan_init
  - drivers/acpi/scan.c:acpi_bus_register_early_device
  - drivers/acpi/scan.c:acpi_bus_check_add
```
**Symbols:**

```
ffffffff815ee920-ffffffff815eefda: acpi_add_single_object (STB_LOCAL)
ffffffff815efa83-ffffffff815efa9a: acpi_add_single_object.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool dep_init</code>
</li>
<li>
<b>Param removed. </b>
<code>long long unsigned int sta</code>
</li>
</ul>
</details>
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
