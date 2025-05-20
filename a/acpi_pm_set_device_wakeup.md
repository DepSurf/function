# Function: <code>acpi_pm_set_device_wakeup</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff814fa4b0)
Location: drivers/acpi/device_pm.c:733
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff814fa4b0-ffffffff814fa597: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8153baa0)
Location: drivers/acpi/device_pm.c:816
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff8153baa0-ffffffff8153bab9: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815718f0)
Location: drivers/acpi/device_pm.c:816
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff815718f0-ffffffff81571909: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815896c0)
Location: drivers/acpi/device_pm.c:817
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff815896c0-ffffffff815896d9: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815ba200)
Location: drivers/acpi/device_pm.c:861
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff815ba200-ffffffff815ba219: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815db440)
Location: drivers/acpi/device_pm.c:866
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff815db440-ffffffff815db459: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81685db0)
Location: drivers/acpi/device_pm.c:866
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff81685db0-ffffffff81685dc9: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816a3a50)
Location: drivers/acpi/device_pm.c:851
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff816a3a50-ffffffff816a3bac: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff81686f60)
Location: drivers/acpi/device_pm.c:848
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff81686f60-ffffffff816870bc: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff816fc3f0)
Location: drivers/acpi/device_pm.c:848
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff816fc3f0-ffffffff816fc546: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff818290f0)
Location: drivers/acpi/device_pm.c:874
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff818290f0-ffffffff8182921d: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff8195b410)
Location: drivers/acpi/device_pm.c:936
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff8195b410-ffffffff8195b53f: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819a18e0)
Location: drivers/acpi/device_pm.c:936
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff819a18e0-ffffffff819a1a0f: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff819e9f90)
Location: drivers/acpi/device_pm.c:949
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_resume
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff819e9f90-ffffffff819ea0bf: acpi_pm_set_device_wakeup (STB_GLOBAL)
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
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffff8000107680f0)
Location: drivers/acpi/device_pm.c:866
Inline: False
Direct callers:
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffff8000107680f0-ffff800010768128: acpi_pm_set_device_wakeup (STB_GLOBAL)
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
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cdc10)
Location: drivers/acpi/device_pm.c:866
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
**Symbols:**

```
ffffffff815cdc10-ffffffff815cdc29: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815b7790)
Location: drivers/acpi/device_pm.c:866
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
```
**Symbols:**

```
ffffffff815b7790-ffffffff815b77a9: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815cf720)
Location: drivers/acpi/device_pm.c:866
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff815cf720-ffffffff815cf739: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_pm_set_device_wakeup(struct device *dev, bool enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/device_pm.c (ffffffff815e95e0)
Location: drivers/acpi/device_pm.c:866
Inline: False
Direct callers:
  - drivers/pnp/pnpacpi/core.c:pnpacpi_suspend
  - drivers/ata/libata-zpodd.c:zpodd_disable_run_wake
  - drivers/ata/libata-zpodd.c:zpodd_enable_run_wake
```
**Symbols:**

```
ffffffff815e95e0-ffffffff815e95f9: acpi_pm_set_device_wakeup (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
