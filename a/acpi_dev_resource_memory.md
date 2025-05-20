# Function: <code>acpi_dev_resource_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81481fa8)
Location: drivers/acpi/resource.c:87
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_tis.c:tpm_check_resource
```
**Symbols:**

```
ffffffff81481fa8-ffffffff81482024: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814d0aa1)
Location: drivers/acpi/resource.c:100
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_tis.c:tpm_check_resource
```
**Symbols:**

```
ffffffff814d0aa1-ffffffff814d0b1d: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814f2b03)
Location: drivers/acpi/resource.c:113
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_tis.c:tpm_check_resource
```
**Symbols:**

```
ffffffff814f2b03-ffffffff814f2b7f: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff814ffe60)
Location: drivers/acpi/resource.c:113
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff814ffe60-ffffffff814ffedd: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81542010)
Location: drivers/acpi/resource.c:113
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81542010-ffffffff8154208d: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81577f60)
Location: drivers/acpi/resource.c:113
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff81577f60-ffffffff81577fdd: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8158fbd0)
Location: drivers/acpi/resource.c:113
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff8158fbd0-ffffffff8158fc4d: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815c0a10)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff815c0a10-ffffffff815c0a8d: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815e1cd0)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff815e1cd0-ffffffff815e1d4d: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168d010)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff8168d010-ffffffff8168d093: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff816aad10)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff816aad10-ffffffff816aad93: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff8168d5a0)
Location: drivers/acpi/resource.c:106
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff8168d5a0-ffffffff8168d623: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81702dd0)
Location: drivers/acpi/resource.c:106
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff81702dd0-ffffffff81702e53: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81830cf0)
Location: drivers/acpi/resource.c:106
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/resource.c:acpi_dev_process_resource
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff81830cf0-ffffffff81830d87: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff81963ea0)
Location: drivers/acpi/resource.c:106
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/resource.c:acpi_dev_process_resource
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff81963ea0-ffffffff81963f37: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819aa340)
Location: drivers/acpi/resource.c:106
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/resource.c:acpi_dev_process_resource
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff819aa340-ffffffff819aa3d7: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff819f45d0)
Location: drivers/acpi/resource.c:106
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/resource.c:acpi_dev_process_resource
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff819f45d0-ffffffff819f4667: acpi_dev_resource_memory (STB_GLOBAL)
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
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffff80001076e578)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
  - drivers/perf/xgene_pmu.c:acpi_pmu_dev_add_resource
```
**Symbols:**

```
ffff80001076e578-ffff80001076e640: acpi_dev_resource_memory (STB_GLOBAL)
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
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d3f90)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff815d3f90-ffffffff815d400d: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815bdb50)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff815bdb50-ffffffff815bdbcd: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815d5fb0)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff815d5fb0-ffffffff815d602d: acpi_dev_resource_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool acpi_dev_resource_memory(struct acpi_resource *ares, struct resource *res);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/resource.c (ffffffff815efe70)
Location: drivers/acpi/resource.c:105
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_get_resource_memory
  - drivers/acpi/resource.c:is_memory
  - drivers/acpi/acpi_lpss.c:is_memory
  - drivers/acpi/acpi_apd.c:misc_check_res
  - drivers/acpi/ioapic.c:setup_res
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
  - drivers/char/tpm/tpm_crb.c:crb_check_resource
```
**Symbols:**

```
ffffffff815efe70-ffffffff815efeed: acpi_dev_resource_memory (STB_GLOBAL)
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
