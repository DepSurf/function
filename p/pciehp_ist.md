# Function: <code>pciehp_ist</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815522d0)
Location: drivers/pci/hotplug/pciehp_hpc.c:602
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff815522d0-ffffffff8155248a: pciehp_ist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:604
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff81582220-ffffffff81582347: pciehp_ist (STB_LOCAL)
ffffffff81582ded-ffffffff81582e6d: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:616
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff815a3c50-ffffffff815a3d96: pciehp_ist (STB_LOCAL)
ffffffff815a47cd-ffffffff815a4842: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:666
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff8164c870-ffffffff8164c98d: pciehp_ist (STB_LOCAL)
ffffffff8164d42a-ffffffff8164d49f: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:669
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff81670bc0-ffffffff81670cdd: pciehp_ist (STB_LOCAL)
ffffffff81bfc271-ffffffff81bfc2e6: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:695
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff81653070-ffffffff81653207: pciehp_ist (STB_LOCAL)
ffffffff81bee0e4-ffffffff81bee1d1: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:697
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff816c4de0-ffffffff816c4f7f: pciehp_ist (STB_LOCAL)
ffffffff81ce8efc-ffffffff81ce8ff7: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:699
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff817eaae0-ffffffff817eac72: pciehp_ist (STB_LOCAL)
ffffffff81eaff98-ffffffff81eb0096: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:699
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff81910d10-ffffffff81910f84: pciehp_ist (STB_LOCAL)
ffffffff8208f8fa-ffffffff8208f90f: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:693
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff81954430-ffffffff81954686: pciehp_ist (STB_LOCAL)
ffffffff8210fc5a-ffffffff8210fc6f: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:694
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff8199d8c0-ffffffff8199db16: pciehp_ist (STB_LOCAL)
ffffffff821ed982-ffffffff821ed997: pciehp_ist.cold (STB_LOCAL)
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
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070c7a8)
Location: drivers/pci/hotplug/pciehp_hpc.c:616
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffff80001070c7a8-ffff80001070c960: pciehp_ist (STB_LOCAL)
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
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d9042)
Location: drivers/pci/hotplug/pciehp_hpc.c:616
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffe0004d9042-ffffffe0004d91c0: pciehp_ist (STB_LOCAL)
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
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:616
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff81597460-ffffffff815975a6: pciehp_ist (STB_LOCAL)
ffffffff81597fdd-ffffffff81598052: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:616
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff815865f0-ffffffff81586736: pciehp_ist (STB_LOCAL)
ffffffff8158716d-ffffffff815871e2: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:616
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff815979a0-ffffffff81597ae6: pciehp_ist (STB_LOCAL)
ffffffff8159851d-ffffffff81598592: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_ist(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:616
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
```
**Symbols:**

```
ffffffff815b1de0-ffffffff815b1f26: pciehp_ist (STB_LOCAL)
ffffffff815b2961-ffffffff815b29d6: pciehp_ist.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
