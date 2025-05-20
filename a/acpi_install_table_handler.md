# Function: <code>acpi_install_table_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814a5ce1)
Location: drivers/acpi/acpica/tbxface.c:409
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_sysfs_init
```
**Symbols:**

```
ffffffff814a5ce1-ffffffff814a5d41: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff814f4fbb)
Location: drivers/acpi/acpica/tbxface.c:409
Inline: True
```
**Symbols:**

```
ffffffff814f4fbb-ffffffff814f501b: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81517c85)
Location: drivers/acpi/acpica/tbxface.c:459
Inline: True
```
**Symbols:**

```
ffffffff81517c85-ffffffff81517ce5: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8152845e)
Location: drivers/acpi/acpica/tbxface.c:459
Inline: True
```
**Symbols:**

```
ffffffff8152845e-ffffffff815284be: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8157fc3a)
Location: drivers/acpi/acpica/tbxface.c:491
Inline: True
```
**Symbols:**

```
ffffffff8157fc3a-ffffffff8157fd19: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815b6e31)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffffffff815b6e31-ffffffff815b6f10: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815d01ee)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffffffff815d01ee-ffffffff815d02cd: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81601a83)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffffffff81601a83-ffffffff81601b66: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81622f2c)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffffffff81622f2c-ffffffff8162300f: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf4c7)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff816cf4c7-ffffffff816cf5aa: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816ed4c7)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff816ed4c7-ffffffff816ed5aa: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816cf383)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff816cf383-ffffffff816cf466: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff817469f3)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff817469f3-ffffffff81746ad6: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81878968)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff81878968-ffffffff81878a56: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff819bad50)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff819bad50-ffffffff819bae73: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a01ef0)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff81a01ef0-ffffffff81a02013: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff81a4cd70)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: False
Direct callers:
  - drivers/acpi/bus.c:acpi_bus_init
```
**Symbols:**

```
ffffffff81a4cd70-ffffffff81a4ce93: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffff8000107983fc)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffff8000107983fc-ffff800010798474: acpi_install_table_handler (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815fcf02)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffffffff815fcf02-ffffffff815fcf66: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff815e8428)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffffffff815e8428-ffffffff815e848c: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff8161720c)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffffffff8161720c-ffffffff816172ef: acpi_install_table_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_install_table_handler(acpi_table_handler handler, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/tbxface.c (ffffffff816310bc)
Location: drivers/acpi/acpica/tbxface.c:457
Inline: True
Direct callers:
  - drivers/acpi/bus.c:acpi_init
```
**Symbols:**

```
ffffffff816310bc-ffffffff8163119f: acpi_install_table_handler (STB_GLOBAL)
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
