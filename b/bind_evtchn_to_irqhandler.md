# Function: <code>bind_evtchn_to_irqhandler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8ac0)
Location: drivers/xen/events/events_base.c:1021
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814c8ac0-ffffffff814c8b36: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81519600)
Location: drivers/xen/events/events_base.c:1032
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81519600-ffffffff81519669: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545ad0)
Location: drivers/xen/events/events_base.c:1031
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81545ad0-ffffffff81545b39: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559930)
Location: drivers/xen/events/events_base.c:1023
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81559930-ffffffff81559998: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bdd80)
Location: drivers/xen/events/events_base.c:1023
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815bdd80-ffffffff815bdde8: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f63e0)
Location: drivers/xen/events/events_base.c:1021
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815f63e0-ffffffff815f6448: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81611480)
Location: drivers/xen/events/events_base.c:1021
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81611480-ffffffff816114e8: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81645240)
Location: drivers/xen/events/events_base.c:1022
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81645240-ffffffff816452ac: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816677e0)
Location: drivers/xen/events/events_base.c:1022
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff816677e0-ffffffff8166784c: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717900)
Location: drivers/xen/events/events_base.c:1037
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront_split
  - drivers/net/xen-netfront.c:setup_netfront_split
```
**Symbols:**

```
ffffffff81717900-ffffffff81717984: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734eb0)
Location: drivers/xen/events/events_base.c:1406
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront_split
  - drivers/net/xen-netfront.c:setup_netfront_split
```
**Symbols:**

```
ffffffff81734eb0-ffffffff81734f3b: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718450)
Location: drivers/xen/events/events_base.c:1444
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81718450-ffffffff817184dd: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795d80)
Location: drivers/xen/events/events_base.c:1450
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
```
**Symbols:**

```
ffffffff81795d80-ffffffff81795e0d: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cecf0)
Location: drivers/xen/events/events_base.c:1450
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
**Symbols:**

```
ffffffff818cecf0-ffffffff818ced9e: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a20190)
Location: drivers/xen/events/events_base.c:1452
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
**Symbols:**

```
ffffffff81a20190-ffffffff81a2023e: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a69520)
Location: drivers/xen/events/events_base.c:1445
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
**Symbols:**

```
ffffffff81a69520-ffffffff81a695ce: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(evtchn_port_t evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abbab0)
Location: drivers/xen/events/events_base.c:1445
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_init
```
**Symbols:**

```
ffffffff81abbab0-ffffffff81abbb9f: bind_evtchn_to_irqhandler (STB_GLOBAL)
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108315f8)
Location: drivers/xen/events/events_base.c:1022
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff8000108315f8-ffff800010831694: bind_evtchn_to_irqhandler (STB_GLOBAL)
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d510)
Location: drivers/xen/events/events_base.c:1026
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8162d510-ffffffff8162d57c: bind_evtchn_to_irqhandler (STB_GLOBAL)
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
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165b620)
Location: drivers/xen/events/events_base.c:1022
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8165b620-ffffffff8165b68c: bind_evtchn_to_irqhandler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bind_evtchn_to_irqhandler(unsigned int evtchn, irq_handler_t handler, long unsigned int irqflags, const char *devname, void *dev_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675c10)
Location: drivers/xen/events/events_base.c:1022
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xb_init_comms
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81675c10-ffffffff81675c7c: bind_evtchn_to_irqhandler (STB_GLOBAL)
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
