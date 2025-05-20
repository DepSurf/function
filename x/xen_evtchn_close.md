# Function: <code>xen_evtchn_close</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_evtchn_close(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c79f0)
Location: drivers/xen/events/events_base.c:456
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:__startup_pirq
  - drivers/xen/events/events_base.c:__unbind_from_irq
```
**Symbols:**

```
ffffffff814c79f0-ffffffff814c7a52: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xen_evtchn_close(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518460)
Location: drivers/xen/events/events_base.c:456
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81518460-ffffffff815184c2: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_evtchn_close(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81544970)
Location: drivers/xen/events/events_base.c:455
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81544970-ffffffff815449d2: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_evtchn_close(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81558750)
Location: drivers/xen/events/events_base.c:447
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81558750-ffffffff815587b2: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_evtchn_close(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bcb90)
Location: drivers/xen/events/events_base.c:447
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff815bcb90-ffffffff815bcbf2: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xen_evtchn_close(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5230)
Location: drivers/xen/events/events_base.c:447
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff815f5230-ffffffff815f5292: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xen_evtchn_close(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81610320)
Location: drivers/xen/events/events_base.c:447
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81610320-ffffffff81610382: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81644fd8)
Location: drivers/xen/events/events_base.c:448
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81644100-ffffffff8164410b: xen_evtchn_close.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81667588)
Location: drivers/xen/events/events_base.c:448
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff816666b0-ffffffff816666bb: xen_evtchn_close.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_evtchn_close(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817172eb)
Location: drivers/xen/events/events_base.c:462
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81715c40-ffffffff81715c4b: xen_evtchn_close.part.0 (STB_LOCAL)
ffffffff81715c50-ffffffff81715c9c: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_evtchn_close(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81733dea)
Location: drivers/xen/events/events_base.c:786
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81732810-ffffffff8173281b: xen_evtchn_close.part.0 (STB_LOCAL)
ffffffff81732820-ffffffff8173286c: xen_evtchn_close (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xen_evtchn_close(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717896)
Location: drivers/xen/events/events_base.c:816
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff817163e0-ffffffff817163eb: xen_evtchn_close.part.0 (STB_LOCAL)
ffffffff817163f0-ffffffff8171643c: xen_evtchn_close (STB_LOCAL)
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
In drivers/xen/events/events_base.c (ffffffff81794e75)
Location: drivers/xen/events/events_base.c:816
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff818cdb17)
Location: drivers/xen/events/events_base.c:816
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81a1f137)
Location: drivers/xen/events/events_base.c:818
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81a68329)
Location: include/xen/events.h:144
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
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
In drivers/xen/events/events_base.c (ffffffff81ab99a2)
Location: include/xen/events.h:138
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:shutdown_pirq
  - drivers/xen/events/events_base.c:__startup_pirq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void xen_evtchn_close(unsigned int port);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010830060)
Location: drivers/xen/events/events_base.c:448
Inline: True
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffff800010830060-ffff8000108300c4: xen_evtchn_close (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d2b8)
Location: drivers/xen/events/events_base.c:452
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff8162c3e0-ffffffff8162c3eb: xen_evtchn_close.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165b3c8)
Location: drivers/xen/events/events_base.c:448
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff8165a4f0-ffffffff8165a4fb: xen_evtchn_close.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816759b8)
Location: drivers/xen/events/events_base.c:448
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
Direct callers:
  - drivers/xen/events/events_base.c:__unbind_from_irq
  - drivers/xen/events/events_base.c:__startup_pirq
```
**Symbols:**

```
ffffffff81674ae0-ffffffff81674aeb: xen_evtchn_close.part.0 (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
