# Function: <code>acpi_check_resource_conflict</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81479c22)
Location: drivers/acpi/osl.c:1621
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81479c22-ffffffff81479c9d: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814c81e7)
Location: drivers/acpi/osl.c:1433
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff814c81e7-ffffffff814c8262: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814ea0f7)
Location: drivers/acpi/osl.c:1428
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff814ea0f7-ffffffff814ea172: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff814f5e10)
Location: drivers/acpi/osl.c:1427
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff814f5e10-ffffffff814f5e92: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81536750)
Location: drivers/acpi/osl.c:1437
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81536750-ffffffff815367d2: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (0)
Location: drivers/acpi/osl.c:1442
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8156d762-ffffffff8156d796: acpi_check_resource_conflict.cold.17 (STB_LOCAL)
ffffffff8156c3c0-ffffffff8156c417: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8158533f)
Location: drivers/acpi/osl.c:1448
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81585322-ffffffff81585356: acpi_check_resource_conflict.cold.18 (STB_LOCAL)
ffffffff81583ff0-ffffffff81584047: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b5fa1)
Location: drivers/acpi/osl.c:1434
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815b5f84-ffffffff815b5fb8: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff815b4c00-ffffffff815b4c57: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815d71d1)
Location: drivers/acpi/osl.c:1454
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815d71b4-ffffffff815d71e8: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff815d5e30-ffffffff815d5e87: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8167fa3b)
Location: drivers/acpi/osl.c:1454
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_check_region
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8167f990-ffffffff8167f9de: acpi_check_resource_conflict.part.0 (STB_LOCAL)
ffffffff81680ef4-ffffffff81680f28: acpi_check_resource_conflict.part.0.cold (STB_LOCAL)
ffffffff81680f7c-ffffffff81680fb0: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff8167fbf0-ffffffff8167fc47: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8169e4eb)
Location: drivers/acpi/osl.c:1458
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_check_region
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8169e440-ffffffff8169e48e: acpi_check_resource_conflict.part.0 (STB_LOCAL)
ffffffff81c0085c-ffffffff81c00890: acpi_check_resource_conflict.part.0.cold (STB_LOCAL)
ffffffff81c008e4-ffffffff81c00918: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff8169e6a0-ffffffff8169e6f7: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff81681335)
Location: drivers/acpi/osl.c:1458
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/acpi/osl.c:acpi_check_region
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81bf233f-ffffffff81bf237c: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff81681180-ffffffff816811d6: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff816f6415)
Location: drivers/acpi/osl.c:1458
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/acpi/osl.c:acpi_check_region
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81ceebcd-ffffffff81ceec0a: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff816f6260-ffffffff816f62b6: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff818231b5)
Location: drivers/acpi/osl.c:1460
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_check_region
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81eb6328-ffffffff81eb636c: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff81822e20-ffffffff81822e73: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819542a5)
Location: drivers/acpi/osl.c:1460
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_check_region
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff81953e70-ffffffff81953f1a: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff8199a6b5)
Location: drivers/acpi/osl.c:1460
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_check_region
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff8199a270-ffffffff8199a31a: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffffffff819e2b35)
Location: drivers/acpi/osl.c:1454
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_check_region
Direct callers:
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff819e26f0-ffffffff819e279a: acpi_check_resource_conflict (STB_GLOBAL)
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
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/osl.c (ffff800010763600)
Location: drivers/acpi/osl.c:1454
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffff800010763600-ffff800010763698: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/acpi.h:767
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/acpi.h:767
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/acpi.h:767
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815ca746)
Location: drivers/acpi/osl.c:1454
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815ca729-ffffffff815ca75d: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff815c9b90-ffffffff815c9be7: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815b37c6)
Location: drivers/acpi/osl.c:1454
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815b37a9-ffffffff815b37dd: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff815b2c20-ffffffff815b2c77: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815cb4b1)
Location: drivers/acpi/osl.c:1454
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815cb494-ffffffff815cb4c8: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff815ca110-ffffffff815ca167: acpi_check_resource_conflict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int acpi_check_resource_conflict(const struct resource *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/osl.c (ffffffff815e5351)
Location: drivers/acpi/osl.c:1454
Inline: True
Direct callers:
  - drivers/acpi/osl.c:acpi_check_region
  - drivers/mfd/mfd-core.c:mfd_add_device
```
**Symbols:**

```
ffffffff815e5334-ffffffff815e5368: acpi_check_resource_conflict.cold (STB_LOCAL)
ffffffff815e3f70-ffffffff815e3fc7: acpi_check_resource_conflict (STB_GLOBAL)
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
