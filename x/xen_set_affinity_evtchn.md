# Function: <code>xen_set_affinity_evtchn</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xen_set_affinity_evtchn(struct irq_desc *desc, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816449c0)
Location: drivers/xen/events/events_base.c:1345
Inline: False
```
**Symbols:**

```
ffffffff816449c0-ffffffff816449f9: xen_set_affinity_evtchn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xen_set_affinity_evtchn(struct irq_desc *desc, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81666f70)
Location: drivers/xen/events/events_base.c:1345
Inline: False
```
**Symbols:**

```
ffffffff81666f70-ffffffff81666fa9: xen_set_affinity_evtchn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xen_set_affinity_evtchn(struct irq_desc *desc, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81716d80)
Location: drivers/xen/events/events_base.c:1347
Inline: False
```
**Symbols:**

```
ffffffff81716d80-ffffffff81716db4: xen_set_affinity_evtchn (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xen_set_affinity_evtchn(struct irq_desc *desc, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010830c38)
Location: drivers/xen/events/events_base.c:1345
Inline: False
```
**Symbols:**

```
ffff800010830c38-ffff800010830c88: xen_set_affinity_evtchn (STB_GLOBAL)
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
int xen_set_affinity_evtchn(struct irq_desc *desc, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162cca0)
Location: drivers/xen/events/events_base.c:1349
Inline: False
```
**Symbols:**

```
ffffffff8162cca0-ffffffff8162ccd9: xen_set_affinity_evtchn (STB_GLOBAL)
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
int xen_set_affinity_evtchn(struct irq_desc *desc, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165adb0)
Location: drivers/xen/events/events_base.c:1345
Inline: False
```
**Symbols:**

```
ffffffff8165adb0-ffffffff8165ade9: xen_set_affinity_evtchn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xen_set_affinity_evtchn(struct irq_desc *desc, unsigned int tcpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816753a0)
Location: drivers/xen/events/events_base.c:1345
Inline: False
```
**Symbols:**

```
ffffffff816753a0-ffffffff816753d9: xen_set_affinity_evtchn (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
