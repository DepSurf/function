# Function: <code>restore_cpu_ipis</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9a4a)
Location: drivers/xen/events/events_base.c:1451
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151a58c)
Location: drivers/xen/events/events_base.c:1474
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81546a7c)
Location: drivers/xen/events/events_base.c:1469
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155a855)
Location: drivers/xen/events/events_base.c:1468
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bed88)
Location: drivers/xen/events/events_base.c:1468
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1466
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1466
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1475
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1475
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void restore_cpu_ipis(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817168f0)
Location: drivers/xen/events/events_base.c:1478
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
**Symbols:**

```
ffffffff817168f0-ffffffff81716a39: restore_cpu_ipis (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void restore_cpu_ipis(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734490)
Location: drivers/xen/events/events_base.c:1951
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
**Symbols:**

```
ffffffff81734490-ffffffff817345db: restore_cpu_ipis (STB_LOCAL)
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
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1998
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
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
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:2004
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
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
In drivers/xen/events/events_base.c (ffffffff818d08f3)
Location: drivers/xen/events/events_base.c:2004
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
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
In drivers/xen/events/events_base.c (ffffffff81a220f0)
Location: drivers/xen/events/events_base.c:2006
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
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
In drivers/xen/events/events_base.c (ffffffff81a6b487)
Location: drivers/xen/events/events_base.c:2003
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
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
In drivers/xen/events/events_base.c (ffffffff81abd536)
Location: drivers/xen/events/events_base.c:1985
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1475
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1479
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1475
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1475
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_resume
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
