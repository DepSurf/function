# Function: <code>bind_virq_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9310)
Location: drivers/xen/events/events_base.c:961
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff814c9310-ffffffff814c9520: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81519e00)
Location: drivers/xen/events/events_base.c:972
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81519e00-ffffffff8151a024: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815462d0)
Location: drivers/xen/events/events_base.c:971
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff815462d0-ffffffff8154651c: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155a0f0)
Location: drivers/xen/events/events_base.c:963
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff8155a0f0-ffffffff8155a342: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815be540)
Location: drivers/xen/events/events_base.c:963
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff815be540-ffffffff815be789: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f6b80)
Location: drivers/xen/events/events_base.c:961
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff815f6b80-ffffffff815f6dba: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611c10)
Location: drivers/xen/events/events_base.c:961
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81611c10-ffffffff81611e4a: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:962
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff816464d1-ffffffff816464e4: bind_virq_to_irq.cold (STB_LOCAL)
ffffffff81645990-ffffffff81645b99: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81667f30)
Location: drivers/xen/events/events_base.c:962
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81667f30-ffffffff8166812f: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718100)
Location: drivers/xen/events/events_base.c:977
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_initial_domain_console_init
```
**Symbols:**

```
ffffffff81718100-ffffffff817183dd: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735690)
Location: drivers/xen/events/events_base.c:1322
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_initial_domain_console_init
```
**Symbols:**

```
ffffffff81735690-ffffffff81735972: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718c90)
Location: drivers/xen/events/events_base.c:1360
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81718c90-ffffffff81718f72: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81796810)
Location: drivers/xen/events/events_base.c:1366
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81796810-ffffffff81796c0f: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cf700)
Location: drivers/xen/events/events_base.c:1366
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff818cf700-ffffffff818cfb9e: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a20e50)
Location: drivers/xen/events/events_base.c:1368
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81a20e50-ffffffff81a212ee: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6a1e0)
Location: drivers/xen/events/events_base.c:1361
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81a6a1e0-ffffffff81a6a67e: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abc490)
Location: drivers/xen/events/events_base.c:1357
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81abc490-ffffffff81abc8a2: bind_virq_to_irq (STB_GLOBAL)
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
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010831ee8)
Location: drivers/xen/events/events_base.c:962
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffff800010831ee8-ffff80001083213c: bind_virq_to_irq (STB_GLOBAL)
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
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162dc60)
Location: drivers/xen/events/events_base.c:966
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff8162dc60-ffffffff8162de5f: bind_virq_to_irq (STB_GLOBAL)
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
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165bd70)
Location: drivers/xen/events/events_base.c:962
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff8165bd70-ffffffff8165bf6f: bind_virq_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bind_virq_to_irq(unsigned int virq, unsigned int cpu, bool percpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81676360)
Location: drivers/xen/events/events_base.c:962
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff81676360-ffffffff8167655f: bind_virq_to_irq (STB_GLOBAL)
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
