# Function: <code>evtchn_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8c20)
Location: drivers/xen/events/events_base.c:1188
Inline: False
```
**Symbols:**

```
ffffffff814c8c20-ffffffff814c8c4f: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81519740)
Location: drivers/xen/events/events_base.c:1199
Inline: False
```
**Symbols:**

```
ffffffff81519740-ffffffff8151976f: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81545c10)
Location: drivers/xen/events/events_base.c:1198
Inline: False
```
**Symbols:**

```
ffffffff81545c10-ffffffff81545c3f: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81559a60)
Location: drivers/xen/events/events_base.c:1190
Inline: False
```
**Symbols:**

```
ffffffff81559a60-ffffffff81559a80: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bdeb0)
Location: drivers/xen/events/events_base.c:1190
Inline: False
```
**Symbols:**

```
ffffffff815bdeb0-ffffffff815bded0: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f6500)
Location: drivers/xen/events/events_base.c:1188
Inline: False
```
**Symbols:**

```
ffffffff815f6500-ffffffff815f6520: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816115a0)
Location: drivers/xen/events/events_base.c:1188
Inline: False
```
**Symbols:**

```
ffffffff816115a0-ffffffff816115c0: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/events/events_base.c (0)
Location: drivers/xen/events/events_base.c:1189
Inline: False
```
**Symbols:**

```
ffffffff81646484-ffffffff81646497: evtchn_put.cold (STB_LOCAL)
ffffffff81645370-ffffffff81645390: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81667910)
Location: drivers/xen/events/events_base.c:1189
Inline: False
```
**Symbols:**

```
ffffffff81667910-ffffffff81667930: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void evtchn_put(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81717830)
Location: drivers/xen/events/events_base.c:1204
Inline: False
```
**Symbols:**

```
ffffffff81717830-ffffffff81717876: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void evtchn_put(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81734f40)
Location: drivers/xen/events/events_base.c:1586
Inline: False
```
**Symbols:**

```
ffffffff81734f40-ffffffff81734f86: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void evtchn_put(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718550)
Location: drivers/xen/events/events_base.c:1623
Inline: False
```
**Symbols:**

```
ffffffff81718550-ffffffff81718596: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void evtchn_put(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81795fe0)
Location: drivers/xen/events/events_base.c:1629
Inline: False
```
**Symbols:**

```
ffffffff81795fe0-ffffffff81796026: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void evtchn_put(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818cee30)
Location: drivers/xen/events/events_base.c:1629
Inline: False
```
**Symbols:**

```
ffffffff818cee30-ffffffff818cee83: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void evtchn_put(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a204c0)
Location: drivers/xen/events/events_base.c:1631
Inline: False
```
**Symbols:**

```
ffffffff81a204c0-ffffffff81a20513: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void evtchn_put(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a69850)
Location: drivers/xen/events/events_base.c:1625
Inline: False
```
**Symbols:**

```
ffffffff81a69850-ffffffff81a698a3: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void evtchn_put(evtchn_port_t evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81abb6e0)
Location: drivers/xen/events/events_base.c:1614
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_disconnect_backend
```
**Symbols:**

```
ffffffff81abb6e0-ffffffff81abb779: evtchn_put (STB_GLOBAL)
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
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff8000108317a8)
Location: drivers/xen/events/events_base.c:1189
Inline: False
```
**Symbols:**

```
ffff8000108317a8-ffff8000108317f0: evtchn_put (STB_GLOBAL)
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
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162d640)
Location: drivers/xen/events/events_base.c:1193
Inline: False
```
**Symbols:**

```
ffffffff8162d640-ffffffff8162d660: evtchn_put (STB_GLOBAL)
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
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165b750)
Location: drivers/xen/events/events_base.c:1189
Inline: False
```
**Symbols:**

```
ffffffff8165b750-ffffffff8165b770: evtchn_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void evtchn_put(unsigned int evtchn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81675d40)
Location: drivers/xen/events/events_base.c:1189
Inline: False
```
**Symbols:**

```
ffffffff81675d40-ffffffff81675d60: evtchn_put (STB_GLOBAL)
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
