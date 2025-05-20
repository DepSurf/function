# Function: <code>rebind_evtchn_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c9810)
Location: drivers/xen/events/events_base.c:1264
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff814c9810-ffffffff814c98e7: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8151a340)
Location: drivers/xen/events/events_base.c:1276
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff8151a340-ffffffff8151a41f: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81546830)
Location: drivers/xen/events/events_base.c:1274
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81546830-ffffffff8154690f: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8155a650)
Location: drivers/xen/events/events_base.c:1266
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff8155a650-ffffffff8155a71c: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bea90)
Location: drivers/xen/events/events_base.c:1266
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff815bea90-ffffffff815beb5c: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f70c0)
Location: drivers/xen/events/events_base.c:1264
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff815f70c0-ffffffff815f7187: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81612160)
Location: drivers/xen/events/events_base.c:1264
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81612160-ffffffff81612227: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1265
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff8164650d-ffffffff81646520: rebind_evtchn_irq.cold (STB_LOCAL)
ffffffff81645ee0-ffffffff81645fa2: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81668460)
Location: drivers/xen/events/events_base.c:1265
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81668460-ffffffff8166852b: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rebind_evtchn_irq(evtchn_port_t evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817185f0)
Location: drivers/xen/events/events_base.c:1267
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff817185f0-ffffffff8171870b: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rebind_evtchn_irq(evtchn_port_t evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735cb0)
Location: drivers/xen/events/events_base.c:1711
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81735cb0-ffffffff81735d9e: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rebind_evtchn_irq(evtchn_port_t evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817194c0)
Location: drivers/xen/events/events_base.c:1753
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff817194c0-ffffffff817195c1: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rebind_evtchn_irq(evtchn_port_t evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81797370)
Location: drivers/xen/events/events_base.c:1759
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81797370-ffffffff817974ab: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rebind_evtchn_irq(evtchn_port_t evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818d0350)
Location: drivers/xen/events/events_base.c:1759
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff818d0350-ffffffff818d04a2: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rebind_evtchn_irq(evtchn_port_t evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a21b10)
Location: drivers/xen/events/events_base.c:1761
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81a21b10-ffffffff81a21c62: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rebind_evtchn_irq(evtchn_port_t evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6aea0)
Location: drivers/xen/events/events_base.c:1758
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81a6aea0-ffffffff81a6aff2: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rebind_evtchn_irq(evtchn_port_t evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abd060)
Location: drivers/xen/events/events_base.c:1735
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81abd060-ffffffff81abd169: rebind_evtchn_irq (STB_GLOBAL)
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
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010832470)
Location: drivers/xen/events/events_base.c:1265
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffff800010832470-ffff80001083255c: rebind_evtchn_irq (STB_GLOBAL)
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
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162e190)
Location: drivers/xen/events/events_base.c:1269
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff8162e190-ffffffff8162e25b: rebind_evtchn_irq (STB_GLOBAL)
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
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165c2a0)
Location: drivers/xen/events/events_base.c:1265
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff8165c2a0-ffffffff8165c36b: rebind_evtchn_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rebind_evtchn_irq(int evtchn, int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81676890)
Location: drivers/xen/events/events_base.c:1265
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
  - drivers/tty/hvc/hvc_xen.c:xen_console_resume
```
**Symbols:**

```
ffffffff81676890-ffffffff8167695b: rebind_evtchn_irq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int evtchn</code> ➡️ <code>evtchn_port_t evtchn</code>
</li>
</ul>
</details>
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
