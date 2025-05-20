# Function: <code>bind_ipi_to_irqhandler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c95a0)
Location: drivers/xen/events/events_base.c:1083
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff814c95a0-ffffffff814c9764: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151a0b0)
Location: drivers/xen/events/events_base.c:1094
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff8151a0b0-ffffffff8151a284: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815465a0)
Location: drivers/xen/events/events_base.c:1093
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff815465a0-ffffffff81546774: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155a3d0)
Location: drivers/xen/events/events_base.c:1085
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff8155a3d0-ffffffff8155a595: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815be810)
Location: drivers/xen/events/events_base.c:1085
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff815be810-ffffffff815be9d5: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f6e40)
Location: drivers/xen/events/events_base.c:1083
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff815f6e40-ffffffff815f700f: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611ed0)
Location: drivers/xen/events/events_base.c:1083
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff81611ed0-ffffffff8161209f: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1084
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff816464e4-ffffffff816464f7: bind_ipi_to_irqhandler.cold (STB_LOCAL)
ffffffff81645c20-ffffffff81645de4: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816681b0)
Location: drivers/xen/events/events_base.c:1084
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff816681b0-ffffffff8166836a: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718470)
Location: drivers/xen/events/events_base.c:1099
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff81718470-ffffffff817184fb: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735a10)
Location: drivers/xen/events/events_base.c:1481
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff81735a10-ffffffff81735a9b: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81719010)
Location: drivers/xen/events/events_base.c:1518
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff81719010-ffffffff8171927f: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81796ca0)
Location: drivers/xen/events/events_base.c:1524
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff81796ca0-ffffffff81797063: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cfc50)
Location: drivers/xen/events/events_base.c:1524
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff818cfc50-ffffffff818d000f: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a213c0)
Location: drivers/xen/events/events_base.c:1526
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff81a213c0-ffffffff81a2177f: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6a750)
Location: drivers/xen/events/events_base.c:1519
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff81a6a750-ffffffff81a6ab0f: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abc9c0)
Location: drivers/xen/events/events_base.c:1519
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff81abc9c0-ffffffff81abcdd9: bind_ipi_to_irqhandler (STB_GLOBAL)
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108321e8)
Location: drivers/xen/events/events_base.c:1084
Inline: False
```
**Symbols:**

```
ffff8000108321e8-ffff8000108323c8: bind_ipi_to_irqhandler (STB_GLOBAL)
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162dee0)
Location: drivers/xen/events/events_base.c:1088
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff8162dee0-ffffffff8162e09a: bind_ipi_to_irqhandler (STB_GLOBAL)
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
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165bff0)
Location: drivers/xen/events/events_base.c:1084
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff8165bff0-ffffffff8165c1aa: bind_ipi_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bind_ipi_to_irqhandler(enum ipi_vector ipi, unsigned int cpu, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816765e0)
Location: drivers/xen/events/events_base.c:1084
Inline: False
Direct callers:
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp.c:xen_smp_intr_init
  - arch/x86/xen/smp_pv.c:xen_smp_intr_init_pv
  - arch/x86/xen/spinlock.c:xen_init_lock_cpu
```
**Symbols:**

```
ffffffff816765e0-ffffffff8167679a: bind_ipi_to_irqhandler (STB_GLOBAL)
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
