# Function: <code>hub_port_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81605750)
Location: drivers/usb/core/hub.c:961
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81605750-ffffffff81605936: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81665500)
Location: drivers/usb/core/hub.c:963
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81665500-ffffffff816656e3: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81693020)
Location: drivers/usb/core/hub.c:4141
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81693020-ffffffff8169316e: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a86c0)
Location: drivers/usb/core/hub.c:4160
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff816a86c0-ffffffff816a87fb: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81713ac0)
Location: drivers/usb/core/hub.c:4163
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81713ac0-ffffffff81713bfb: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81752830)
Location: drivers/usb/core/hub.c:4214
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81752830-ffffffff8175296b: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81776cb0)
Location: drivers/usb/core/hub.c:4276
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81776cb0-ffffffff81776deb: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4323
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
ffffffff817b4d60-ffffffff817b4e8a: hub_port_disable (STB_LOCAL)
ffffffff817ba304-ffffffff817ba339: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
ffffffff817e5490-ffffffff817e55ba: hub_port_disable (STB_LOCAL)
ffffffff817eab54-ffffffff817eab89: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4385
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_handle_remote_wakeup
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff818b4560-ffffffff818b472d: hub_port_disable (STB_LOCAL)
ffffffff818b9fbd-ffffffff818b9fee: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4403
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_handle_remote_wakeup
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff818c2ed0-ffffffff818c308e: hub_port_disable (STB_LOCAL)
ffffffff81c1aae3-ffffffff81c1ab14: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4523
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff818a5fa0-ffffffff818a615e: hub_port_disable (STB_LOCAL)
ffffffff81c0c929-ffffffff81c0c95a: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4527
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff8193ae00-ffffffff8193afbe: hub_port_disable (STB_LOCAL)
ffffffff81d13897-ffffffff81d138c8: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4533
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81a929e0-ffffffff81a92bbc: hub_port_disable (STB_LOCAL)
ffffffff81ede63b-ffffffff81ede66a: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c14b90)
Location: drivers/usb/core/hub.c:4529
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81c14b90-ffffffff81c14d80: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7b990)
Location: drivers/usb/core/hub.c:4549
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81c7b990-ffffffff81c7bb7f: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d305e0)
Location: drivers/usb/core/hub.c:4558
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
ffffffff81d305e0-ffffffff81d307cf: hub_port_disable (STB_LOCAL)
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
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a14290)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
ffff800010a14290-ffff800010a143f0: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aec354)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
c0aec354-c0aec4a4: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acc010)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:hub_port_logical_disconnect
```
**Symbols:**

```
c000000000acc010-c000000000acc204: hub_port_disable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000639394)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
ffffffe000639394-ffffffe0006394ba: hub_port_disable (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
ffffffff8179d870-ffffffff8179d99a: hub_port_disable (STB_LOCAL)
ffffffff817a2f34-ffffffff817a2f69: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
ffffffff8178f4f0-ffffffff8178f61a: hub_port_disable (STB_LOCAL)
ffffffff81794d74-ffffffff81794da9: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
ffffffff817da310-ffffffff817da43a: hub_port_disable (STB_LOCAL)
ffffffff817df9d4-ffffffff817dfa09: hub_port_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hub_port_disable(struct usb_hub *hub, int port1, int set_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4371
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:usb_port_disable
  - drivers/usb/core/hub.c:usb_port_disable
```
**Symbols:**

```
ffffffff817f45a0-ffffffff817f46ca: hub_port_disable (STB_LOCAL)
ffffffff817f9cc4-ffffffff817f9cf9: hub_port_disable.cold (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
