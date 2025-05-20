# Function: <code>acpi_processor_get_performance_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff814aeec9)
Location: drivers/acpi/processor_perflib.c:426
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
```
**Symbols:**

```
ffffffff814aeec9-ffffffff814af097: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff814fe58d)
Location: drivers/acpi/processor_perflib.c:426
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
```
**Symbols:**

```
ffffffff814fe58d-ffffffff814fe9d7: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81521281)
Location: drivers/acpi/processor_perflib.c:424
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
```
**Symbols:**

```
ffffffff81521281-ffffffff815216cb: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81532c10)
Location: drivers/acpi/processor_perflib.c:422
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
```
**Symbols:**

```
ffffffff81532c10-ffffffff8153318d: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff815941c0)
Location: drivers/acpi/processor_perflib.c:422
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
```
**Symbols:**

```
ffffffff815941c0-ffffffff815948a3: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:423
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff815cc5d2-ffffffff815cc643: acpi_processor_get_performance_info.cold.10 (STB_LOCAL)
ffffffff815cbb50-ffffffff815cbd7e: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:423
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff815e5bb2-ffffffff815e5c23: acpi_processor_get_performance_info.cold.11 (STB_LOCAL)
ffffffff815e5130-ffffffff815e535e: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:410
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff816177aa-ffffffff8161781b: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff81616d20-ffffffff81616f54: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:396
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81638dc2-ffffffff81638e33: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff81638280-ffffffff816384b4: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:396
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff816e5b97-ffffffff816e5ba8: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff816e5120-ffffffff816e5219: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:395
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81c02df8-ffffffff81c02e09: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff81702b90-ffffffff81702c89: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:394
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81bf4842-ffffffff81bf4853: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff816e43f0-ffffffff816e44ce: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:392
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81cf195f-ffffffff81cf1970: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff8175d090-ffffffff8175d16b: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:392
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81eb98d4-ffffffff81eb98e5: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff81890c60-ffffffff81890d44: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff819d7d30)
Location: drivers/acpi/processor_perflib.c:389
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff819d7d30-ffffffff819d7e32: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a1f730)
Location: drivers/acpi/processor_perflib.c:411
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81a1f730-ffffffff81a1f832: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a6aa50)
Location: drivers/acpi/processor_perflib.c:411
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81a6aa50-ffffffff81a6ab52: acpi_processor_get_performance_info (STB_GLOBAL)
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
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffff8000107a34c0)
Location: drivers/acpi/processor_perflib.c:396
Inline: True
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
```
**Symbols:**

```
ffff8000107a34c0-ffff8000107a3908: acpi_processor_get_performance_info (STB_GLOBAL)
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
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:396
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81607de7-ffffffff81607e58: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff81607380-ffffffff8160756a: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:396
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
```
**Symbols:**

```
ffffffff815f2eec-ffffffff815f2f5d: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff815f2480-ffffffff815f266a: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:396
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff8162d0a2-ffffffff8162d113: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff8162c560-ffffffff8162c794: acpi_processor_get_performance_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_performance_info(struct acpi_processor *pr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:396
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_register_performance
  - drivers/xen/xen-acpi-processor.c:xen_acpi_processor_init
```
**Symbols:**

```
ffffffff81646f42-ffffffff81646fb3: acpi_processor_get_performance_info.cold (STB_LOCAL)
ffffffff81646400-ffffffff81646634: acpi_processor_get_performance_info (STB_GLOBAL)
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
