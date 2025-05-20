# Function: <code>acpi_nvs_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffffffff8147b223)
Location: drivers/acpi/nvs.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_mark_nvs_memory
```
**Symbols:**

```
ffffffff8147b223-ffffffff8147b372: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffffffff814c982f)
Location: drivers/acpi/nvs.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_mark_nvs_memory
```
**Symbols:**

```
ffffffff814c982f-ffffffff814c997a: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffffffff814eb773)
Location: drivers/acpi/nvs.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820_mark_nvs_memory
```
**Symbols:**

```
ffffffff814eb773-ffffffff814eb8be: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffffffff814f7a50)
Location: drivers/acpi/nvs.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff814f7a50-ffffffff814f7ba8: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffffffff81538e00)
Location: drivers/acpi/nvs.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff81538e00-ffffffff81538f58: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff8156edc9-ffffffff8156eedb: acpi_nvs_register.cold.4 (STB_LOCAL)
ffffffff8156ec50-ffffffff8156ec8f: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff81586989-ffffffff81586a9b: acpi_nvs_register.cold.3 (STB_LOCAL)
ffffffff81586810-ffffffff8158684f: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff815b7639-ffffffff815b774f: acpi_nvs_register.cold (STB_LOCAL)
ffffffff815b74c0-ffffffff815b74ff: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff815d8869-ffffffff815d897f: acpi_nvs_register.cold (STB_LOCAL)
ffffffff815d86f0-ffffffff815d872f: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff81682838-ffffffff81682870: acpi_nvs_register.cold (STB_LOCAL)
ffffffff816825b0-ffffffff816825ed: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff81c00bc4-ffffffff81c00bfc: acpi_nvs_register.cold (STB_LOCAL)
ffffffff816a0e40-ffffffff816a0e7d: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff81bf2512-ffffffff81bf2625: acpi_nvs_register.cold (STB_LOCAL)
ffffffff81683c30-ffffffff81683c6f: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff81ceee2e-ffffffff81ceef41: acpi_nvs_register.cold (STB_LOCAL)
ffffffff816f8dd0-ffffffff816f8e0f: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff81eb65a5-ffffffff81eb66b8: acpi_nvs_register.cold (STB_LOCAL)
ffffffff81825fc0-ffffffff8182600b: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffffffff819576e0)
Location: drivers/acpi/nvs.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff819576e0-ffffffff81957835: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffffffff8199dba0)
Location: drivers/acpi/nvs.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff8199dba0-ffffffff8199dcf5: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffffffff819e61b0)
Location: drivers/acpi/nvs.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff819e61b0-ffffffff819e6369: acpi_nvs_register (STB_GLOBAL)
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
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/nvs.c (ffff800010765cf8)
Location: drivers/acpi/nvs.c:36
Inline: False
```
**Symbols:**

```
ffff800010765cf8-ffff800010765d68: acpi_nvs_register (STB_GLOBAL)
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
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff815cbb99-ffffffff815cbcaf: acpi_nvs_register.cold (STB_LOCAL)
ffffffff815cba20-ffffffff815cba5f: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff815b4be9-ffffffff815b4cff: acpi_nvs_register.cold (STB_LOCAL)
ffffffff815b4a70-ffffffff815b4aaf: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff815ccb49-ffffffff815ccc5f: acpi_nvs_register.cold (STB_LOCAL)
ffffffff815cc9d0-ffffffff815cca0f: acpi_nvs_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_nvs_register(__u64 start, __u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/nvs.c (0)
Location: drivers/acpi/nvs.c:36
Inline: False
Direct callers:
  - arch/x86/kernel/e820.c:e820__register_nvs_regions
```
**Symbols:**

```
ffffffff815e69e9-ffffffff815e6aff: acpi_nvs_register.cold (STB_LOCAL)
ffffffff815e6870-ffffffff815e68af: acpi_nvs_register (STB_GLOBAL)
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
