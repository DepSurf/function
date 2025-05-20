# Function: <code>xen_destroy_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9170)
Location: drivers/xen/events/events_base.c:763
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff814c9170-ffffffff814c929e: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81519c60)
Location: drivers/xen/events/events_base.c:774
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff81519c60-ffffffff81519d8e: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81546130)
Location: drivers/xen/events/events_base.c:773
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff81546130-ffffffff8154625e: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559f50)
Location: drivers/xen/events/events_base.c:765
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff81559f50-ffffffff8155a073: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815be3a0)
Location: drivers/xen/events/events_base.c:765
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff815be3a0-ffffffff815be4c3: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:763
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff815f75f9-ffffffff815f7612: xen_destroy_irq.cold.25 (STB_LOCAL)
ffffffff815f69f0-ffffffff815f6b10: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:763
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff816126b4-ffffffff816126cc: xen_destroy_irq.cold.24 (STB_LOCAL)
ffffffff81611a80-ffffffff81611b95: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:764
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff816464b5-ffffffff816464d1: xen_destroy_irq.cold (STB_LOCAL)
ffffffff81645820-ffffffff81645917: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:764
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff81668998-ffffffff816689b4: xen_destroy_irq.cold (STB_LOCAL)
ffffffff81667dc0-ffffffff81667eb7: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:778
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff81718aba-ffffffff81718ad6: xen_destroy_irq.cold (STB_LOCAL)
ffffffff81717f70-ffffffff8171808a: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1099
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81c04fcb-ffffffff81c04fe7: xen_destroy_irq.cold (STB_LOCAL)
ffffffff81735500-ffffffff8173561a: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1136
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81bf6c14-ffffffff81bf6c2c: xen_destroy_irq.cold (STB_LOCAL)
ffffffff81718b10-ffffffff81718c13: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1136
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_pv_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81cf58db-ffffffff81cf58f3: xen_destroy_irq.cold (STB_LOCAL)
ffffffff81796680-ffffffff817967a0: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1136
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81ebda21-ffffffff81ebda3b: xen_destroy_irq.cold (STB_LOCAL)
ffffffff818cf540-ffffffff818cf685: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a20c60)
Location: drivers/xen/events/events_base.c:1138
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81a20c60-ffffffff81a20db7: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a69ff0)
Location: drivers/xen/events/events_base.c:1131
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81a69ff0-ffffffff81a6a147: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abc320)
Location: drivers/xen/events/events_base.c:1147
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irqs
```
**Symbols:**

```
ffffffff81abc320-ffffffff81abc476: xen_destroy_irq (STB_GLOBAL)
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
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010831d20)
Location: drivers/xen/events/events_base.c:764
Inline: False
```
**Symbols:**

```
ffff800010831d20-ffff800010831e48: xen_destroy_irq (STB_GLOBAL)
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
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:768
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff8162e7c8-ffffffff8162e7e4: xen_destroy_irq.cold (STB_LOCAL)
ffffffff8162daf0-ffffffff8162dbe7: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:764
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff8165c7d8-ffffffff8165c7f4: xen_destroy_irq.cold (STB_LOCAL)
ffffffff8165bc00-ffffffff8165bcf7: xen_destroy_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xen_destroy_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:764
Inline: False
Direct callers:
  - arch/x86/pci/xen.c:xen_teardown_msi_irq
```
**Symbols:**

```
ffffffff81676dc8-ffffffff81676de4: xen_destroy_irq.cold (STB_LOCAL)
ffffffff816761f0-ffffffff816762e7: xen_destroy_irq (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
