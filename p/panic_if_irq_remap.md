# Function: <code>panic_if_irq_remap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/irq_remapping.c (ffffffff8153dfe0)
Location: drivers/iommu/irq_remapping.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff8153dfe0-ffffffff8153dffa: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/irq_remapping.c (ffffffff81592fb0)
Location: drivers/iommu/irq_remapping.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81592fb0-ffffffff81592fca: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/irq_remapping.c (ffffffff815c0870)
Location: drivers/iommu/irq_remapping.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff815c0870-ffffffff815c088a: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/irq_remapping.c (ffffffff815d63b0)
Location: drivers/iommu/irq_remapping.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff815d63b0-ffffffff815d63ca: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/irq_remapping.c (ffffffff8163d160)
Location: drivers/iommu/irq_remapping.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff8163d160-ffffffff8163d17a: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:153
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81678828-ffffffff8167882d: panic_if_irq_remap.cold.0 (STB_LOCAL)
ffffffff816787b0-ffffffff816787c9: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:152
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81697909-ffffffff8169790e: panic_if_irq_remap.cold.0 (STB_LOCAL)
ffffffff81697890-ffffffff816978a9: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff816d02b9-ffffffff816d02be: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff816d0240-ffffffff816d0259: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff816f40d9-ffffffff816f40de: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff816f4060-ffffffff816f4079: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff817ac7c9-ffffffff817ac7ce: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff817ac750-ffffffff817ac769: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81c0d852-ffffffff81c0d857: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff817c13f0-ffffffff817c1409: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81bffba2-ffffffff81bffbab: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff817a45f0-ffffffff817a4604: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81d020fc-ffffffff81d02105: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff8182dde0-ffffffff8182ddf4: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81eca5fd-ffffffff81eca606: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff8196eb20-ffffffff8196eb3c: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/irq_remapping.c (ffffffff81ad94b0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81ad94b0-ffffffff81ad94d1: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/irq_remapping.c (ffffffff81b27630)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81b27630-ffffffff81b27651: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/irq_remapping.c (ffffffff81b7e4c0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81b7e4c0-ffffffff81b7e4e1: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff816b98c9-ffffffff816b98ce: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff816b9850-ffffffff816b9869: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81697509-ffffffff8169750e: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff81697490-ffffffff816974a9: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff816e7d99-ffffffff816e7d9e: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff816e7d20-ffffffff816e7d39: panic_if_irq_remap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void panic_if_irq_remap(const char *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/iommu/irq_remapping.c (0)
Location: drivers/iommu/irq_remapping.c:156
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:check_timer
```
**Symbols:**

```
ffffffff81702499-ffffffff8170249e: panic_if_irq_remap.cold (STB_LOCAL)
ffffffff81702420-ffffffff81702439: panic_if_irq_remap (STB_GLOBAL)
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
