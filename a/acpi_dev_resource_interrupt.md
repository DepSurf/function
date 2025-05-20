# Function: <code>acpi_dev_resource_interrupt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81481e8a)
Location: drivers/acpi/resource.c:408
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_tis.c:tpm_check_resource
```
**Symbols:**

```
ffffffff81481e8a-ffffffff81481f35: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814d0983)
Location: drivers/acpi/resource.c:446
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_tis.c:tpm_check_resource
```
**Symbols:**

```
ffffffff814d0983-ffffffff814d0a2e: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814f29e5)
Location: drivers/acpi/resource.c:459
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_tis.c:tpm_check_resource
```
**Symbols:**

```
ffffffff814f29e5-ffffffff814f2a90: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81500340)
Location: drivers/acpi/resource.c:459
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81500340-ffffffff81500402: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815424f0)
Location: drivers/acpi/resource.c:460
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815424f0-ffffffff815425b2: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81578450)
Location: drivers/acpi/resource.c:460
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81578450-ffffffff81578512: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815900c0)
Location: drivers/acpi/resource.c:460
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815900c0-ffffffff81590182: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815c0ea0)
Location: drivers/acpi/resource.c:452
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff815c0ea0-ffffffff815c0f62: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815e2160)
Location: drivers/acpi/resource.c:452
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff815e2160-ffffffff815e2222: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168ceb0)
Location: drivers/acpi/resource.c:452
Inline: False
Direct callers:
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff8168ceb0-ffffffff8168cf72: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816aabb0)
Location: drivers/acpi/resource.c:445
Inline: False
Direct callers:
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff816aabb0-ffffffff816aac72: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168d450)
Location: drivers/acpi/resource.c:490
Inline: False
Direct callers:
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff8168d450-ffffffff8168d50f: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81702c80)
Location: drivers/acpi/resource.c:497
Inline: False
Direct callers:
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff81702c80-ffffffff81702d3f: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81830880)
Location: drivers/acpi/resource.c:497
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_process_resource
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_resource
```
**Symbols:**

```
ffffffff81830880-ffffffff81830954: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81964580)
Location: drivers/acpi/resource.c:612
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_process_resource
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource
```
**Symbols:**

```
ffffffff81964580-ffffffff8196465b: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819aaa50)
Location: drivers/acpi/resource.c:653
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_process_resource
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource
```
**Symbols:**

```
ffffffff819aaa50-ffffffff819aab11: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819f4d20)
Location: drivers/acpi/resource.c:716
Inline: False
Direct callers:
  - drivers/acpi/resource.c:acpi_dev_process_resource
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_add_irq_resource
```
**Symbols:**

```
ffffffff819f4d20-ffffffff819f4de1: acpi_dev_resource_interrupt (STB_GLOBAL)
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
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffff80001076ea78)
Location: drivers/acpi/resource.c:452
Inline: True
Direct callers:
  - drivers/acpi/evged.c:acpi_ged_request_interrupt
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffff80001076ea78-ffff80001076eb94: acpi_dev_resource_interrupt (STB_GLOBAL)
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
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d4420)
Location: drivers/acpi/resource.c:452
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff815d4420-ffffffff815d44e2: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815bdfe0)
Location: drivers/acpi/resource.c:452
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff815bdfe0-ffffffff815be0a2: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d6440)
Location: drivers/acpi/resource.c:452
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff815d6440-ffffffff815d6502: acpi_dev_resource_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool acpi_dev_resource_interrupt(struct acpi_resource *ares, int index, struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815f0300)
Location: drivers/acpi/resource.c:452
Inline: True
Direct callers:
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/spi/spi.c:acpi_spi_add_resource
```
**Symbols:**

```
ffffffff815f0300-ffffffff815f03c2: acpi_dev_resource_interrupt (STB_GLOBAL)
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
