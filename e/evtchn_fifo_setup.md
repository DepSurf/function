# Function: <code>evtchn_fifo_setup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff814cae30)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff814cae30-ffffffff814cb050: evtchn_fifo_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8151b9b0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff8151b9b0-ffffffff8151bc2a: evtchn_fifo_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81547e80)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81547e80-ffffffff815480fa: evtchn_fifo_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff8155b980)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff8155b980-ffffffff8155bc03: evtchn_fifo_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff815bfca0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff815bfca0-ffffffff815bff23: evtchn_fifo_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff815f8370-ffffffff815f8529: evtchn_fifo_setup (STB_LOCAL)
ffffffff815f87cf-ffffffff815f8846: evtchn_fifo_setup.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff816136d0-ffffffff81613889: evtchn_fifo_setup (STB_LOCAL)
ffffffff8161389c-ffffffff81613913: evtchn_fifo_setup.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff816474f0-ffffffff81647686: evtchn_fifo_setup (STB_LOCAL)
ffffffff8164769a-ffffffff81647708: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81669990-ffffffff81669b26: evtchn_fifo_setup (STB_LOCAL)
ffffffff81669b3a-ffffffff81669ba8: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81719710-ffffffff817198b5: evtchn_fifo_setup (STB_LOCAL)
ffffffff81719c55-ffffffff81719cc3: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81736960-ffffffff81736b03: evtchn_fifo_setup (STB_LOCAL)
ffffffff81c0537c-ffffffff81c053ea: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff8171a450-ffffffff8171a5e5: evtchn_fifo_setup (STB_LOCAL)
ffffffff81bf6fe2-ffffffff81bf7050: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81798b70-ffffffff81798d52: evtchn_fifo_setup (STB_LOCAL)
ffffffff81cf5d5c-ffffffff81cf5e09: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff818d1d90-ffffffff818d1f8e: evtchn_fifo_setup (STB_LOCAL)
ffffffff81ebde3e-ffffffff81ebdeea: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evtchn_fifo_setup(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a23f00)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81a23f00-ffffffff81a241dd: evtchn_fifo_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evtchn_fifo_setup(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81a6d430)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81a6d430-ffffffff81a6d720: evtchn_fifo_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evtchn_fifo_setup(evtchn_port_t port);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffffffff81abf4a0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81abf4a0-ffffffff81abf790: evtchn_fifo_setup (STB_LOCAL)
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
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_fifo.c (ffff800010833ad0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffff800010833ad0-ffff800010833c80: evtchn_fifo_setup (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff8162f800-ffffffff8162f996: evtchn_fifo_setup (STB_LOCAL)
ffffffff8162f9aa-ffffffff8162fa18: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff8165d7d0-ffffffff8165d966: evtchn_fifo_setup (STB_LOCAL)
ffffffff8165d97a-ffffffff8165d9e8: evtchn_fifo_setup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int evtchn_fifo_setup(struct irq_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_fifo.c (0)
Location: drivers/xen/events/events_fifo.c:141
Inline: False
```
**Symbols:**

```
ffffffff81677de0-ffffffff81677f76: evtchn_fifo_setup (STB_LOCAL)
ffffffff81677f8a-ffffffff81677ff8: evtchn_fifo_setup.cold (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>evtchn_port_t port</code>
</li>
<li>
<b>Param removed. </b>
<code>struct irq_info *info</code>
</li>
</ul>
</details>
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
