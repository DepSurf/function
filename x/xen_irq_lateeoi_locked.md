# Function: <code>xen_irq_lateeoi_locked</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81732ebb)
Location: drivers/xen/events/events_base.c:591
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
**Symbols:**

```
ffffffff81732a60-ffffffff81732b7d: xen_irq_lateeoi_locked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8171696b)
Location: drivers/xen/events/events_base.c:608
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
**Symbols:**

```
ffffffff817161b0-ffffffff817163de: xen_irq_lateeoi_locked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81793d06)
Location: drivers/xen/events/events_base.c:608
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
**Symbols:**

```
ffffffff81793440-ffffffff817936de: xen_irq_lateeoi_locked.part.0 (STB_LOCAL)
ffffffff81cf5818-ffffffff81cf5859: xen_irq_lateeoi_locked.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cc814)
Location: drivers/xen/events/events_base.c:608
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
**Symbols:**

```
ffffffff818cbf40-ffffffff818cc203: xen_irq_lateeoi_locked.part.0 (STB_LOCAL)
ffffffff81ebd935-ffffffff81ebd99a: xen_irq_lateeoi_locked.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1de34)
Location: drivers/xen/events/events_base.c:610
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
**Symbols:**

```
ffffffff81a1d3c0-ffffffff81a1d683: xen_irq_lateeoi_locked.part.0 (STB_LOCAL)
ffffffff820946cf-ffffffff82094734: xen_irq_lateeoi_locked.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a67104)
Location: drivers/xen/events/events_base.c:611
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
**Symbols:**

```
ffffffff81a665d0-ffffffff81a668a0: xen_irq_lateeoi_locked.part.0 (STB_LOCAL)
ffffffff82115444-ffffffff82115488: xen_irq_lateeoi_locked.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81aba1a8)
Location: drivers/xen/events/events_base.c:597
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
Direct callers:
  - drivers/xen/events/events_base.c:xen_irq_lateeoi
  - drivers/xen/events/events_base.c:xen_irq_lateeoi_worker
```
**Symbols:**

```
ffffffff81ab9100-ffffffff81ab93be: xen_irq_lateeoi_locked.part.0 (STB_LOCAL)
ffffffff821f30e4-ffffffff821f3128: xen_irq_lateeoi_locked.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
