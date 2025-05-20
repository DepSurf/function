# Function: <code>ec_install_handlers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816f4068)
Location: drivers/acpi/ec.c:1286
Inline: True
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_boot_ec_enable
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
```
**Symbols:**

```
ffffffff816f4068-ffffffff816f410c: ec_install_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ec_install_handlers(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81759028)
Location: drivers/acpi/ec.c:1293
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81759028-ffffffff817590d2: ec_install_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f5773)
Location: drivers/acpi/ec.c:1386
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff814f5773-ffffffff814f5867: ec_install_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81503950)
Location: drivers/acpi/ec.c:1409
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81503950-ffffffff81503b4e: ec_install_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81545db0)
Location: drivers/acpi/ec.c:1411
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81545db0-ffffffff81545fb4: ec_install_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1417
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff8157b250-ffffffff8157b3e1: ec_install_handlers (STB_LOCAL)
ffffffff8157c450-ffffffff8157c461: ec_install_handlers.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1429
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81593a40-ffffffff81593bd1: ec_install_handlers (STB_LOCAL)
ffffffff81594130-ffffffff81594141: ec_install_handlers.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1443
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815c4b30-ffffffff815c4ccd: ec_install_handlers (STB_LOCAL)
ffffffff815c51aa-ffffffff815c51bb: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1417
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815e5d70-ffffffff815e5f0d: ec_install_handlers (STB_LOCAL)
ffffffff815e63d8-ffffffff815e63e9: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690f90)
Location: drivers/acpi/ec.c:1454
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81690f90-ffffffff8169121e: ec_install_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816aecc0)
Location: drivers/acpi/ec.c:1441
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff816aecc0-ffffffff816aef52: ec_install_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816912d0)
Location: drivers/acpi/ec.c:1442
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff816912d0-ffffffff81691562: ec_install_handlers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1459
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81706d80-ffffffff81706fed: ec_install_handlers (STB_LOCAL)
ffffffff81cefa90-ffffffff81cefad6: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1465
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81834ed0-ffffffff81835117: ec_install_handlers (STB_LOCAL)
ffffffff81eb7605-ffffffff81eb7648: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, struct acpi_device *device, bool call_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1463
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81968fe0-ffffffff8196929d: ec_install_handlers (STB_LOCAL)
ffffffff82091b09-ffffffff82091b1e: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, struct acpi_device *device, bool call_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1482
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff819af5d0-ffffffff819af885: ec_install_handlers (STB_LOCAL)
ffffffff8211240d-ffffffff82112422: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, struct acpi_device *device, bool call_reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1482
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff819f9a80-ffffffff819f9d35: ec_install_handlers (STB_LOCAL)
ffffffff821f0175-ffffffff821f018a: ec_install_handlers.cold (STB_LOCAL)
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
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff800010772b70)
Location: drivers/acpi/ec.c:1417
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffff800010772b70-ffff800010772c94: ec_install_handlers (STB_LOCAL)
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
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1417
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815d7c60-ffffffff815d7dfd: ec_install_handlers (STB_LOCAL)
ffffffff815d8298-ffffffff815d82a9: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1417
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815c1820-ffffffff815c19bd: ec_install_handlers (STB_LOCAL)
ffffffff815c1e88-ffffffff815c1e99: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1417
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815da050-ffffffff815da1ed: ec_install_handlers (STB_LOCAL)
ffffffff815da6b8-ffffffff815da6c9: ec_install_handlers.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ec_install_handlers(struct acpi_ec *ec, bool handle_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/ec.c (0)
Location: drivers/acpi/ec.c:1417
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815f3f10-ffffffff815f40ad: ec_install_handlers (STB_LOCAL)
ffffffff815f4578-ffffffff815f4589: ec_install_handlers.cold (STB_LOCAL)
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
<code>bool handle_events</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_device *device</code>
</li>
<li>
<b>Param removed. </b>
<code>bool handle_events</code>
</li>
</ul>
</details>
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
<code>bool call_reg</code>
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
