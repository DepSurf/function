# Function: <code>bind_evtchn_to_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8940)
Location: drivers/xen/events/events_base.c:829
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
```
**Symbols:**

```
ffffffff814c8940-ffffffff814c8a1f: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81519480)
Location: drivers/xen/events/events_base.c:840
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81519480-ffffffff8151955f: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545950)
Location: drivers/xen/events/events_base.c:839
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81545950-ffffffff81545a2f: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815597b0)
Location: drivers/xen/events/events_base.c:831
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff815597b0-ffffffff81559886: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bdc00)
Location: drivers/xen/events/events_base.c:831
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff815bdc00-ffffffff815bdcdc: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f6260)
Location: drivers/xen/events/events_base.c:829
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff815f6260-ffffffff815f6336: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611300)
Location: drivers/xen/events/events_base.c:829
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81611300-ffffffff816113d6: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:830
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff8164645e-ffffffff81646471: bind_evtchn_to_irq.cold (STB_LOCAL)
ffffffff816450b0-ffffffff81645195: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81667660)
Location: drivers/xen/events/events_base.c:830
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81667660-ffffffff8166773b: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bind_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817173d0)
Location: drivers/xen/events/events_base.c:844
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff817173d0-ffffffff81717516: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bind_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734cc0)
Location: drivers/xen/events/events_base.c:1210
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81734cc0-ffffffff81734cd7: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817182d0)
Location: drivers/xen/events/events_base.c:1248
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff817182d0-ffffffff817182e9: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795d40)
Location: drivers/xen/events/events_base.c:1248
Inline: False
```
**Symbols:**

```
ffffffff81795d40-ffffffff81795d59: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818ceae0)
Location: drivers/xen/events/events_base.c:1248
Inline: False
```
**Symbols:**

```
ffffffff818ceae0-ffffffff818ceb03: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a20110)
Location: drivers/xen/events/events_base.c:1250
Inline: False
```
**Symbols:**

```
ffffffff81a20110-ffffffff81a20133: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a694a0)
Location: drivers/xen/events/events_base.c:1243
Inline: False
```
**Symbols:**

```
ffffffff81a694a0-ffffffff81a694c3: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_evtchn_to_irq(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abb470)
Location: drivers/xen/events/events_base.c:1238
Inline: False
```
**Symbols:**

```
ffffffff81abb470-ffffffff81abb493: bind_evtchn_to_irq (STB_GLOBAL)
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
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010831428)
Location: drivers/xen/events/events_base.c:830
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffff800010831428-ffff80001083152c: bind_evtchn_to_irq (STB_GLOBAL)
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
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d390)
Location: drivers/xen/events/events_base.c:834
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff8162d390-ffffffff8162d46b: bind_evtchn_to_irq (STB_GLOBAL)
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
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165b4a0)
Location: drivers/xen/events/events_base.c:830
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff8165b4a0-ffffffff8165b57b: bind_evtchn_to_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bind_evtchn_to_irq(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675a90)
Location: drivers/xen/events/events_base.c:830
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:bind_evtchn_to_irqhandler
  - drivers/xen/events/events_base.c:bind_interdomain_evtchn_to_irq
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
```
**Symbols:**

```
ffffffff81675a90-ffffffff81675b6b: bind_evtchn_to_irq (STB_GLOBAL)
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
<code>unsigned int evtchn</code> ➡️ <code>evtchn_port_t evtchn</code>
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
