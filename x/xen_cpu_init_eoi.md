# Function: <code>xen_cpu_init_eoi</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_cpu_init_eoi(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817326b0)
Location: drivers/xen/events/events_base.c:667
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_evtchn_cpu_prepare
```
**Symbols:**

```
ffffffff817326b0-ffffffff8173271f: xen_cpu_init_eoi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_cpu_init_eoi(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716050)
Location: drivers/xen/events/events_base.c:697
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_evtchn_cpu_prepare
```
**Symbols:**

```
ffffffff81716050-ffffffff817160bf: xen_cpu_init_eoi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_cpu_init_eoi(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817932b0)
Location: drivers/xen/events/events_base.c:697
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_evtchn_cpu_prepare
```
**Symbols:**

```
ffffffff817932b0-ffffffff8179333a: xen_cpu_init_eoi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_cpu_init_eoi(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cbd80)
Location: drivers/xen/events/events_base.c:697
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_evtchn_cpu_prepare
```
**Symbols:**

```
ffffffff818cbd80-ffffffff818cbe1b: xen_cpu_init_eoi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_cpu_init_eoi(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a1d1c0)
Location: drivers/xen/events/events_base.c:699
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_evtchn_cpu_prepare
```
**Symbols:**

```
ffffffff81a1d1c0-ffffffff81a1d25b: xen_cpu_init_eoi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_cpu_init_eoi(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a663d0)
Location: drivers/xen/events/events_base.c:700
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_evtchn_cpu_prepare
```
**Symbols:**

```
ffffffff81a663d0-ffffffff81a6646b: xen_cpu_init_eoi (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_cpu_init_eoi(unsigned int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81ab8f00)
Location: drivers/xen/events/events_base.c:689
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_init_IRQ
  - drivers/xen/events/events_base.c:xen_evtchn_cpu_prepare
```
**Symbols:**

```
ffffffff81ab8f00-ffffffff81ab8f9b: xen_cpu_init_eoi (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
