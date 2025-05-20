# Function: <code>xen_rebind_evtchn_to_cpu</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xen_rebind_evtchn_to_cpu(int evtchn, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81558e90)
Location: drivers/xen/events/events_base.c:1298
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
**Symbols:**

```
ffffffff81558e90-ffffffff81558f71: xen_rebind_evtchn_to_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xen_rebind_evtchn_to_cpu(int evtchn, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd260)
Location: drivers/xen/events/events_base.c:1298
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
**Symbols:**

```
ffffffff815bd260-ffffffff815bd351: xen_rebind_evtchn_to_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xen_rebind_evtchn_to_cpu(int evtchn, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5910)
Location: drivers/xen/events/events_base.c:1296
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
**Symbols:**

```
ffffffff815f5910-ffffffff815f5a04: xen_rebind_evtchn_to_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xen_rebind_evtchn_to_cpu(int evtchn, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816109e0)
Location: drivers/xen/events/events_base.c:1296
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
**Symbols:**

```
ffffffff816109e0-ffffffff81610ad4: xen_rebind_evtchn_to_cpu (STB_GLOBAL)
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
In drivers/xen/events/events_base.c (ffffffff816448c2)
Location: drivers/xen/events/events_base.c:1297
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff81666e72)
Location: drivers/xen/events/events_base.c:1297
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff81716c82)
Location: drivers/xen/events/events_base.c:1299
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff8173417d)
Location: drivers/xen/events/events_base.c:1741
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff81717c91)
Location: drivers/xen/events/events_base.c:1783
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff8179553f)
Location: drivers/xen/events/events_base.c:1789
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff818ce268)
Location: drivers/xen/events/events_base.c:1789
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff81a1f889)
Location: drivers/xen/events/events_base.c:1791
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff81a68bd9)
Location: drivers/xen/events/events_base.c:1788
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff81abb7ea)
Location: drivers/xen/events/events_base.c:1766
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffff800010830b54)
Location: drivers/xen/events/events_base.c:1297
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff8162cba2)
Location: drivers/xen/events/events_base.c:1301
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff8165acb2)
Location: drivers/xen/events/events_base.c:1297
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
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
In drivers/xen/events/events_base.c (ffffffff816752a2)
Location: drivers/xen/events/events_base.c:1297
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:set_affinity_irq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
