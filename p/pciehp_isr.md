# Function: <code>pciehp_isr</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814be8a0)
Location: drivers/pci/hotplug/pciehp_hpc.c:561
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff814be8a0-ffffffff814bec12: pciehp_isr.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c9080)
Location: drivers/pci/hotplug/pciehp_hpc.c:561
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff814c9080-ffffffff814c93b0: pciehp_isr.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81509640)
Location: drivers/pci/hotplug/pciehp_hpc.c:558
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff81509640-ffffffff81509973: pciehp_isr.isra.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153a660)
Location: drivers/pci/hotplug/pciehp_hpc.c:538
Inline: True
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff8153a660-ffffffff8153a96d: pciehp_isr.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815517e0)
Location: drivers/pci/hotplug/pciehp_hpc.c:513
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815517e0-ffffffff81551a4f: pciehp_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:515
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81581740-ffffffff81581990: pciehp_isr (STB_LOCAL)
ffffffff81582d73-ffffffff81582dd0: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:527
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815a3240-ffffffff815a3490: pciehp_isr (STB_LOCAL)
ffffffff815a4753-ffffffff815a47b0: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:563
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8164bdd0-ffffffff8164bfff: pciehp_isr (STB_LOCAL)
ffffffff8164d3b6-ffffffff8164d3f5: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:566
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81670120-ffffffff8167034f: pciehp_isr (STB_LOCAL)
ffffffff81bfc1a8-ffffffff81bfc1e7: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:592
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81652620-ffffffff8165284f: pciehp_isr (STB_LOCAL)
ffffffff81bee020-ffffffff81bee05f: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:592
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff816c4370-ffffffff816c45db: pciehp_isr (STB_LOCAL)
ffffffff81ce8e0f-ffffffff81ce8e77: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:594
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff817e9fc0-ffffffff817ea21e: pciehp_isr (STB_LOCAL)
ffffffff81eafeb8-ffffffff81eaff1f: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:594
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81910060-ffffffff819102fa: pciehp_isr (STB_LOCAL)
ffffffff8208f8d0-ffffffff8208f8fa: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:588
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81953780-ffffffff81953a1a: pciehp_isr (STB_LOCAL)
ffffffff8210fc30-ffffffff8210fc5a: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:589
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff8199cc10-ffffffff8199ceaa: pciehp_isr (STB_LOCAL)
ffffffff821ed958-ffffffff821ed982: pciehp_isr.cold (STB_LOCAL)
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
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffff80001070bcd8)
Location: drivers/pci/hotplug/pciehp_hpc.c:527
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffff80001070bcd8-ffff80001070bfa4: pciehp_isr (STB_LOCAL)
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
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffe0004d86c6)
Location: drivers/pci/hotplug/pciehp_hpc.c:527
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffe0004d86c6-ffffffe0004d88e0: pciehp_isr (STB_LOCAL)
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
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:527
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81596a50-ffffffff81596ca0: pciehp_isr (STB_LOCAL)
ffffffff81597f63-ffffffff81597fc0: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:527
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81585be0-ffffffff81585e30: pciehp_isr (STB_LOCAL)
ffffffff815870f3-ffffffff81587150: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:527
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff81596f90-ffffffff815971e0: pciehp_isr (STB_LOCAL)
ffffffff815984a3-ffffffff81598500: pciehp_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t pciehp_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (0)
Location: drivers/pci/hotplug/pciehp_hpc.c:527
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_poll
  - drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist
```
**Symbols:**

```
ffffffff815b13d0-ffffffff815b1620: pciehp_isr (STB_LOCAL)
ffffffff815b28e7-ffffffff815b2944: pciehp_isr.cold (STB_LOCAL)
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
