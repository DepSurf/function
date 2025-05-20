# Function: <code>acpi_get_phys_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff8148277d)
Location: drivers/acpi/processor_core.c:182
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff8148277d-ffffffff8148296c: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff814d1322)
Location: drivers/acpi/processor_core.c:200
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff814d1322-ffffffff814d146d: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff814f35a3)
Location: drivers/acpi/processor_core.c:220
Inline: False
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff814f35a3-ffffffff814f35b8: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81501290)
Location: drivers/acpi/processor_core.c:198
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff81501290-ffffffff815013e2: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815436c0)
Location: drivers/acpi/processor_core.c:198
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff815436c0-ffffffff81543812: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81579620)
Location: drivers/acpi/processor_core.c:198
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff81579620-ffffffff8157976c: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815912a0)
Location: drivers/acpi/processor_core.c:198
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815912a0-ffffffff815913ec: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815c2100)
Location: drivers/acpi/processor_core.c:199
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815c2100-ffffffff815c2259: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815e33e0)
Location: drivers/acpi/processor_core.c:199
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815e33e0-ffffffff815e3539: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff8168ea15)
Location: drivers/acpi/processor_core.c:199
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_get_cpuid
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff8168e910-ffffffff8168e98d: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff816ac6f3)
Location: drivers/acpi/processor_core.c:196
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_get_cpuid
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff816ac5e0-ffffffff816ac65d: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff8168eb60)
Location: drivers/acpi/processor_core.c:196
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff8168eb60-ffffffff8168ed1b: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81704570)
Location: drivers/acpi/processor_core.c:196
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81704570-ffffffff8170472b: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81832660)
Location: drivers/acpi/processor_core.c:196
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81832660-ffffffff8183282f: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff81965f00)
Location: drivers/acpi/processor_core.c:196
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81965f00-ffffffff819660cf: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff819ac490)
Location: drivers/acpi/processor_core.c:225
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff819ac490-ffffffff819ac65f: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff819f6a21)
Location: drivers/acpi/processor_core.c:254
Inline: True
Inline callers:
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/acpi/processor_core.c:acpi_get_cpuid
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff819f6890-ffffffff819f691c: acpi_get_phys_id (STB_GLOBAL)
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffff80001076fa78)
Location: drivers/acpi/processor_core.c:199
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffff80001076fa78-ffff80001076fc78: acpi_get_phys_id (STB_GLOBAL)
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
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815d5320)
Location: drivers/acpi/processor_core.c:199
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815d5320-ffffffff815d5479: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815beee0)
Location: drivers/acpi/processor_core.c:199
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
```
**Symbols:**

```
ffffffff815beee0-ffffffff815bf039: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815d76c0)
Location: drivers/acpi/processor_core.c:199
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815d76c0-ffffffff815d7819: acpi_get_phys_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
phys_cpuid_t acpi_get_phys_id(acpi_handle handle, int type, u32 acpi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_core.c (ffffffff815f1580)
Location: drivers/acpi/processor_core.c:199
Inline: True
Direct callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_get_info
  - drivers/acpi/processor_core.c:acpi_get_cpuid
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815f1580-ffffffff815f16d9: acpi_get_phys_id (STB_GLOBAL)
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
