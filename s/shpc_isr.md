# Function: <code>shpc_isr</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff8153e1f0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff8153e1f0-ffffffff8153e47f: shpc_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffff815555c0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff815555c0-ffffffff8155584d: shpc_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff81585630-ffffffff81585841: shpc_isr (STB_LOCAL)
ffffffff81586109-ffffffff81586191: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff815a7010-ffffffff815a7221: shpc_isr (STB_LOCAL)
ffffffff815a7ae9-ffffffff815a7b71: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff8164fd20-ffffffff8164ff31: shpc_isr (STB_LOCAL)
ffffffff816507b9-ffffffff81650841: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff816731c0-ffffffff816733d1: shpc_isr (STB_LOCAL)
ffffffff81bfd0e3-ffffffff81bfd16b: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:767
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff816556e0-ffffffff816558fa: shpc_isr (STB_LOCAL)
ffffffff81beefb6-ffffffff81bef03e: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:767
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff816c75e0-ffffffff816c7844: shpc_isr (STB_LOCAL)
ffffffff81cea074-ffffffff81cea18b: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:767
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff817ed610-ffffffff817ed892: shpc_isr (STB_LOCAL)
ffffffff81eb1131-ffffffff81eb1250: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:750
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff81914940-ffffffff81914c5f: shpc_isr (STB_LOCAL)
ffffffff8208fc14-ffffffff8208fcb0: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:750
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff81957f60-ffffffff8195827c: shpc_isr (STB_LOCAL)
ffffffff8210ff70-ffffffff82110004: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:750
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff819a14d0-ffffffff819a17ec: shpc_isr (STB_LOCAL)
ffffffff821edc98-ffffffff821edd2c: shpc_isr.cold (STB_LOCAL)
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
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffff800010710740)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffff800010710740-ffff800010710a40: shpc_isr (STB_LOCAL)
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
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (ffffffe0004dbeec)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffe0004dbeec-ffffffe0004dc22a: shpc_isr (STB_LOCAL)
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
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff8159a820-ffffffff8159aa31: shpc_isr (STB_LOCAL)
ffffffff8159b2f9-ffffffff8159b381: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff815899b0-ffffffff81589bc1: shpc_isr (STB_LOCAL)
ffffffff8158a489-ffffffff8158a511: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff8159ad60-ffffffff8159af71: shpc_isr (STB_LOCAL)
ffffffff8159b839-ffffffff8159b8c1: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
irqreturn_t shpc_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/shpchp_hpc.c (0)
Location: drivers/pci/hotplug/shpchp_hpc.c:772
Inline: False
Direct callers:
  - drivers/pci/hotplug/shpchp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff815b51a0-ffffffff815b53b1: shpc_isr (STB_LOCAL)
ffffffff815b5c69-ffffffff815b5cf1: shpc_isr.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
