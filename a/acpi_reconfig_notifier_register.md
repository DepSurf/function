# Function: <code>acpi_reconfig_notifier_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814ce4a6)
Location: drivers/acpi/scan.c:2136
Inline: False
```
**Symbols:**

```
ffffffff814ce4a6-ffffffff814ce4c0: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f037a)
Location: drivers/acpi/scan.c:2169
Inline: False
```
**Symbols:**

```
ffffffff814f037a-ffffffff814f0394: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fd420)
Location: drivers/acpi/scan.c:2176
Inline: False
```
**Symbols:**

```
ffffffff814fd420-ffffffff814fd43a: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8153f160)
Location: drivers/acpi/scan.c:2291
Inline: False
```
**Symbols:**

```
ffffffff8153f160-ffffffff8153f17a: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815750b0)
Location: drivers/acpi/scan.c:2307
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff815750b0-ffffffff815750ca: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158ceb0)
Location: drivers/acpi/scan.c:2320
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff8158ceb0-ffffffff8158ceca: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bdc60)
Location: drivers/acpi/scan.c:2325
Inline: False
Direct callers:
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff815bdc60-ffffffff815bdc7a: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815def20)
Location: drivers/acpi/scan.c:2326
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff815def20-ffffffff815def3a: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81689ea0)
Location: drivers/acpi/scan.c:2340
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff81689ea0-ffffffff81689eba: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a7a40)
Location: drivers/acpi/scan.c:2485
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff816a7a40-ffffffff816a7a5a: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168a4b0)
Location: drivers/acpi/scan.c:2449
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff8168a4b0-ffffffff8168a4ca: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816ff9b0)
Location: drivers/acpi/scan.c:2641
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff816ff9b0-ffffffff816ff9ca: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182d470)
Location: drivers/acpi/scan.c:2682
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff8182d470-ffffffff8182d492: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819601d0)
Location: drivers/acpi/scan.c:2691
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff819601d0-ffffffff819601f2: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a65c0)
Location: drivers/acpi/scan.c:2735
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff819a65c0-ffffffff819a65e2: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819eefa0)
Location: drivers/acpi/scan.c:2784
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff819eefa0-ffffffff819eefc2: acpi_reconfig_notifier_register (STB_GLOBAL)
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
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076b580)
Location: drivers/acpi/scan.c:2326
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffff80001076b580-ffff80001076b5b8: acpi_reconfig_notifier_register (STB_GLOBAL)
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
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d1400)
Location: drivers/acpi/scan.c:2326
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
```
**Symbols:**

```
ffffffff815d1400-ffffffff815d141a: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bafc0)
Location: drivers/acpi/scan.c:2326
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
```
**Symbols:**

```
ffffffff815bafc0-ffffffff815bafda: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d3200)
Location: drivers/acpi/scan.c:2326
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff815d3200-ffffffff815d321a: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acpi_reconfig_notifier_register(struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815ed0c0)
Location: drivers/acpi/scan.c:2326
Inline: False
Direct callers:
  - drivers/acpi/acpi_platform.c:acpi_platform_init
  - drivers/spi/spi.c:spi_init
  - drivers/i2c/i2c-core-base.c:i2c_init
```
**Symbols:**

```
ffffffff815ed0c0-ffffffff815ed0da: acpi_reconfig_notifier_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
