# Function: <code>bind_virq_to_irqhandler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9520)
Location: drivers/xen/events/events_base.c:1064
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff814c9520-ffffffff814c95a0: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151a030)
Location: drivers/xen/events/events_base.c:1075
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff8151a030-ffffffff8151a0a3: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81546520)
Location: drivers/xen/events/events_base.c:1074
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81546520-ffffffff81546593: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155a350)
Location: drivers/xen/events/events_base.c:1066
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff8155a350-ffffffff8155a3c2: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815be790)
Location: drivers/xen/events/events_base.c:1066
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff815be790-ffffffff815be802: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f6dc0)
Location: drivers/xen/events/events_base.c:1064
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff815f6dc0-ffffffff815f6e32: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611e50)
Location: drivers/xen/events/events_base.c:1064
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81611e50-ffffffff81611ec2: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81645ba0)
Location: drivers/xen/events/events_base.c:1065
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81645ba0-ffffffff81645c16: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81668130)
Location: drivers/xen/events/events_base.c:1065
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81668130-ffffffff816681a6: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817183e0)
Location: drivers/xen/events/events_base.c:1080
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff817183e0-ffffffff8171846e: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735980)
Location: drivers/xen/events/events_base.c:1462
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81735980-ffffffff81735a0e: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718f80)
Location: drivers/xen/events/events_base.c:1499
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81718f80-ffffffff8171900e: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81796c10)
Location: drivers/xen/events/events_base.c:1505
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81796c10-ffffffff81796c9e: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cfba0)
Location: drivers/xen/events/events_base.c:1505
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff818cfba0-ffffffff818cfc4f: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a21300)
Location: drivers/xen/events/events_base.c:1507
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81a21300-ffffffff81a213af: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6a690)
Location: drivers/xen/events/events_base.c:1500
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81a6a690-ffffffff81a6a73f: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abc8c0)
Location: drivers/xen/events/events_base.c:1500
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81abc8c0-ffffffff81abc9b0: bind_virq_to_irqhandler (STB_GLOBAL)
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010832140)
Location: drivers/xen/events/events_base.c:1065
Inline: False
```
**Symbols:**

```
ffff800010832140-ffff8000108321e8: bind_virq_to_irqhandler (STB_GLOBAL)
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162de60)
Location: drivers/xen/events/events_base.c:1069
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff8162de60-ffffffff8162ded6: bind_virq_to_irqhandler (STB_GLOBAL)
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
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165bf70)
Location: drivers/xen/events/events_base.c:1065
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff8165bf70-ffffffff8165bfe6: bind_virq_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bind_virq_to_irqhandler(unsigned int virq, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81676560)
Location: drivers/xen/events/events_base.c:1065
Inline: False
Direct callers:
  - arch/x86/xen/time.c:xen_setup_timer
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - drivers/xen/pcpu.c:xen_pcpu_init
  - drivers/xen/mcelog.c:bind_virq_for_mce
```
**Symbols:**

```
ffffffff81676560-ffffffff816765d6: bind_virq_to_irqhandler (STB_GLOBAL)
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
