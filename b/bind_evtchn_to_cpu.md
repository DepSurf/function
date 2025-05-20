# Function: <code>bind_evtchn_to_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8000)
Location: drivers/xen/events/events_base.c:333
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
```
**Symbols:**

```
ffffffff814c8000-ffffffff814c80af: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518a80)
Location: drivers/xen/events/events_base.c:333
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81518a80-ffffffff81518b45: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81544f80)
Location: drivers/xen/events/events_base.c:332
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81544f80-ffffffff81545033: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81558de0)
Location: drivers/xen/events/events_base.c:332
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81558de0-ffffffff81558e8b: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd1a0)
Location: drivers/xen/events/events_base.c:332
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff815bd1a0-ffffffff815bd251: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5850)
Location: drivers/xen/events/events_base.c:332
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff815f5850-ffffffff815f590d: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81610920)
Location: drivers/xen/events/events_base.c:332
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_rebind_evtchn_to_cpu
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81610920-ffffffff816109d3: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816446a0)
Location: drivers/xen/events/events_base.c:333
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff816446a0-ffffffff81644752: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81666c50)
Location: drivers/xen/events/events_base.c:333
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81666c50-ffffffff81666d02: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817166e0)
Location: drivers/xen/events/events_base.c:347
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff817166e0-ffffffff817167b8: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81733fc0)
Location: drivers/xen/events/events_base.c:505
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:restore_cpu_ipis
  - drivers/xen/events/events_base.c:restore_cpu_virqs
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81733fc0-ffffffff817340ed: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717a80)
Location: drivers/xen/events/events_base.c:522
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81717a80-ffffffff81717bfb: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795280)
Location: drivers/xen/events/events_base.c:522
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81795280-ffffffff81795484: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cdfb0)
Location: drivers/xen/events/events_base.c:522
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff818cdfb0-ffffffff818ce1be: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1f610)
Location: drivers/xen/events/events_base.c:523
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81a1f610-ffffffff81a1f814: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bind_evtchn_to_cpu(evtchn_port_t evtchn, unsigned int cpu, bool force_affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:524
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81a68810-ffffffff81a68b65: bind_evtchn_to_cpu (STB_LOCAL)
ffffffff8211549d-ffffffff821154fd: bind_evtchn_to_cpu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bind_evtchn_to_cpu(struct irq_info *info, unsigned int cpu, bool force_affinity);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:513
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81ab9b60-ffffffff81ab9e23: bind_evtchn_to_cpu (STB_LOCAL)
ffffffff821f313d-ffffffff821f318b: bind_evtchn_to_cpu.cold (STB_LOCAL)
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
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108308a8)
Location: drivers/xen/events/events_base.c:333
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffff8000108308a8-ffff800010830964: bind_evtchn_to_cpu (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162c980)
Location: drivers/xen/events/events_base.c:337
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff8162c980-ffffffff8162ca32: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165aa90)
Location: drivers/xen/events/events_base.c:333
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff8165aa90-ffffffff8165ab42: bind_evtchn_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bind_evtchn_to_cpu(unsigned int chn, unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675080)
Location: drivers/xen/events/events_base.c:333
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:xen_irq_resume
  - drivers/xen/events/events_base.c:set_affinity_irq
  - drivers/xen/events/events_base.c:rebind_evtchn_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81675080-ffffffff81675132: bind_evtchn_to_cpu (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>evtchn_port_t evtchn</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int chn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool force_affinity</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>evtchn_port_t evtchn</code>
</li>
</ul>
</details>
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
