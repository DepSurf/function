# Function: <code>irq_wake_thread</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810db0b0)
Location: kernel/irq/manage.c:993
Inline: False
```
**Symbols:**

```
ffffffff810db0b0-ffffffff810db150: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e0740)
Location: kernel/irq/manage.c:1007
Inline: False
```
**Symbols:**

```
ffffffff810e0740-ffffffff810e07e0: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e7080)
Location: kernel/irq/manage.c:1007
Inline: False
```
**Symbols:**

```
ffffffff810e7080-ffffffff810e711a: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810e6770)
Location: kernel/irq/manage.c:984
Inline: False
```
**Symbols:**

```
ffffffff810e6770-ffffffff810e67f3: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810eea20)
Location: kernel/irq/manage.c:1012
Inline: False
```
**Symbols:**

```
ffffffff810eea20-ffffffff810eeaa3: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff810f6e20)
Location: kernel/irq/manage.c:1049
Inline: False
```
**Symbols:**

```
ffffffff810f6e20-ffffffff810f6e9a: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81102590)
Location: kernel/irq/manage.c:1060
Inline: False
```
**Symbols:**

```
ffffffff81102590-ffffffff8110260a: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/manage.c (0)
Location: kernel/irq/manage.c:1127
Inline: False
```
**Symbols:**

```
ffffffff8110d6e4-ffffffff8110d6f7: irq_wake_thread.cold (STB_LOCAL)
ffffffff8110ad80-ffffffff8110adfa: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81117150)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
ffffffff81117150-ffffffff811171ca: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81122950)
Location: kernel/irq/manage.c:1203
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff81122950-ffffffff811229ca: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111e780)
Location: kernel/irq/manage.c:1277
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff8111e780-ffffffff8111e7fa: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8111ea90)
Location: kernel/irq/manage.c:1277
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_disable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_sysfs_enable_slot
  - drivers/pci/hotplug/pciehp_ctrl.c:pciehp_queue_pushbutton_work
```
**Symbols:**

```
ffffffff8111ea90-ffffffff8111eb0a: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8113ef20)
Location: kernel/irq/manage.c:1301
Inline: False
```
**Symbols:**

```
ffffffff8113ef20-ffffffff8113ef9a: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81162590)
Location: kernel/irq/manage.c:1345
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff81162590-ffffffff81162614: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811960b0)
Location: kernel/irq/manage.c:1337
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff811960b0-ffffffff81196134: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811a7a70)
Location: kernel/irq/manage.c:1343
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff811a7a70-ffffffff811a7af4: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff811b75d0)
Location: kernel/irq/manage.c:1345
Inline: False
Direct callers:
  - drivers/net/phy/phy_device.c:mdio_bus_phy_resume
```
**Symbols:**

```
ffffffff811b75d0-ffffffff811b7654: irq_wake_thread (STB_GLOBAL)
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
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffff80001017a0c0)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
ffff80001017a0c0-ffff80001017a1c0: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c03cabe4)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
c03cabe4-c03cac8c: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (c0000000001d3740)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
c0000000001d3740-c0000000001d3830: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffe000113ba4)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
ffffffe000113ba4-ffffffe000113c2a: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110f730)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
ffffffff8110f730-ffffffff8110f7aa: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81100470)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
ffffffff81100470-ffffffff811004ea: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff8110d620)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
ffffffff8110d620-ffffffff8110d69a: irq_wake_thread (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void irq_wake_thread(unsigned int irq, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/manage.c (ffffffff81118b80)
Location: kernel/irq/manage.c:1120
Inline: False
```
**Symbols:**

```
ffffffff81118b80-ffffffff81118bfa: irq_wake_thread (STB_GLOBAL)
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
