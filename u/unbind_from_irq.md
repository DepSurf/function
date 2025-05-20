# Function: <code>unbind_from_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8a90)
Location: drivers/xen/events/events_base.c:1014
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
```
**Symbols:**

```
ffffffff814c8a90-ffffffff814c8abe: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815195d0)
Location: drivers/xen/events/events_base.c:1025
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff815195d0-ffffffff815195fe: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545aa0)
Location: drivers/xen/events/events_base.c:1024
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff81545aa0-ffffffff81545ace: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559900)
Location: drivers/xen/events/events_base.c:1016
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff81559900-ffffffff8155992e: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bdd50)
Location: drivers/xen/events/events_base.c:1016
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff815bdd50-ffffffff815bdd7e: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f63b0)
Location: drivers/xen/events/events_base.c:1014
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff815f63b0-ffffffff815f63de: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611450)
Location: drivers/xen/events/events_base.c:1014
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff81611450-ffffffff8161147e: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81645200)
Location: drivers/xen/events/events_base.c:1015
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff81645200-ffffffff81645232: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816677a0)
Location: drivers/xen/events/events_base.c:1015
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff816677a0-ffffffff816677d2: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717848)
Location: drivers/xen/events/events_base.c:1030
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734f58)
Location: drivers/xen/events/events_base.c:1379
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718568)
Location: drivers/xen/events/events_base.c:1417
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795ff8)
Location: drivers/xen/events/events_base.c:1423
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cee46)
Location: drivers/xen/events/events_base.c:1423
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a204d6)
Location: drivers/xen/events/events_base.c:1425
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a69866)
Location: drivers/xen/events/events_base.c:1418
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abb700)
Location: drivers/xen/events/events_base.c:1415
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler_lateeoi
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
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
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108315b0)
Location: drivers/xen/events/events_base.c:1015
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffff8000108315b0-ffff8000108315f8: unbind_from_irq (STB_LOCAL)
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
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d4d0)
Location: drivers/xen/events/events_base.c:1019
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff8162d4d0-ffffffff8162d502: unbind_from_irq (STB_LOCAL)
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
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165b5e0)
Location: drivers/xen/events/events_base.c:1015
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff8165b5e0-ffffffff8165b612: unbind_from_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unbind_from_irq(unsigned int irq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675bd0)
Location: drivers/xen/events/events_base.c:1015
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:evtchn_put
  - drivers/xen/events/events_base.c:unbind_from_irqhandler
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
```
**Symbols:**

```
ffffffff81675bd0-ffffffff81675c02: unbind_from_irq (STB_LOCAL)
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
