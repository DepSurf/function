# Function: <code>pstore_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81320b70)
Location: fs/pstore/platform.c:441
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81320b70-ffffffff81320cae: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813561b0)
Location: fs/pstore/platform.c:633
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff813561b0-ffffffff81356302: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff8136c5b0)
Location: fs/pstore/platform.c:668
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff8136c5b0-ffffffff8136c721: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813803d0)
Location: fs/pstore/platform.c:678
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff813803d0-ffffffff813805a5: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff813a53e0)
Location: fs/pstore/platform.c:675
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff813a53e0-ffffffff813a55b5: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:521
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff813d4de2-ffffffff813d4ea8: pstore_register.cold.3 (STB_LOCAL)
ffffffff813d45c0-ffffffff813d47b5: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:563
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff813ef456-ffffffff813ef4ef: pstore_register.cold.3 (STB_LOCAL)
ffffffff813eec70-ffffffff813eedd3: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:556
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff8141b70b-ffffffff8141b7a4: pstore_register.cold (STB_LOCAL)
ffffffff8141af30-ffffffff8141b09e: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:556
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff8143555b-ffffffff814355f4: pstore_register.cold (STB_LOCAL)
ffffffff81434d80-ffffffff81434eee: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:561
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff814852e7-ffffffff8148535c: pstore_register.cold (STB_LOCAL)
ffffffff81484b30-ffffffff81484c9f: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:561
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81bef957-ffffffff81bef9cc: pstore_register.cold (STB_LOCAL)
ffffffff814a2160-ffffffff814a22cf: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:564
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81be1a00-ffffffff81be1a75: pstore_register.cold (STB_LOCAL)
ffffffff814a8200-ffffffff814a8370: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:564
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81cd269b-ffffffff81cd2710: pstore_register.cold (STB_LOCAL)
ffffffff81500520-ffffffff81500690: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:562
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81e85886-ffffffff81e858f3: pstore_register.cold (STB_LOCAL)
ffffffff81591e50-ffffffff81591fae: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff81639290)
Location: fs/pstore/platform.c:574
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81639290-ffffffff8163945c: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff816716d0)
Location: fs/pstore/platform.c:574
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff816716d0-ffffffff8167189c: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffff816acf90)
Location: fs/pstore/platform.c:465
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff816acf90-ffffffff816ad2be: pstore_register (STB_GLOBAL)
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
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffff80001051ad00)
Location: fs/pstore/platform.c:556
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffff80001051ad00-ffff80001051af24: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c06d5114)
Location: fs/pstore/platform.c:556
Inline: False
Direct callers:
  - fs/pstore/ram.c:ramoops_probe
```
**Symbols:**

```
c06d5114-c06d535c: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (c000000000664a20)
Location: fs/pstore/platform.c:556
Inline: False
Direct callers:
  - arch/powerpc/kernel/nvram_64.c:nvram_init_oops_partition
```
**Symbols:**

```
c000000000664a20-c000000000664e68: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pstore/platform.c (ffffffe000383d22)
Location: fs/pstore/platform.c:556
Inline: False
```
**Symbols:**

```
ffffffe000383d22-ffffffe000383f7a: pstore_register (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:556
Inline: False
```
**Symbols:**

```
ffffffff8142db3b-ffffffff8142dbd4: pstore_register.cold (STB_LOCAL)
ffffffff8142d360-ffffffff8142d4ce: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:556
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff8141e5bb-ffffffff8141e654: pstore_register.cold (STB_LOCAL)
ffffffff8141dde0-ffffffff8141df4e: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:556
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81429cdb-ffffffff81429d74: pstore_register.cold (STB_LOCAL)
ffffffff81429500-ffffffff8142966e: pstore_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int pstore_register(struct pstore_info *psi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/pstore/platform.c (0)
Location: fs/pstore/platform.c:556
Inline: False
Direct callers:
  - drivers/acpi/apei/erst.c:erst_init
```
**Symbols:**

```
ffffffff81440b9b-ffffffff81440c36: pstore_register.cold (STB_LOCAL)
ffffffff814403c0-ffffffff81440529: pstore_register (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
