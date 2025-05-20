# Function: <code>hub_ext_port_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816042e0)
Location: drivers/usb/core/hub.c:556
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff816042e0-ffffffff81604414: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81663fd0)
Location: drivers/usb/core/hub.c:558
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_port_disable
  - drivers/usb/core/hub.c:hub_port_disable
```
**Symbols:**

```
ffffffff81663fd0-ffffffff81664107: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81691f10)
Location: drivers/usb/core/hub.c:561
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81691f10-ffffffff81692047: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a73c0)
Location: drivers/usb/core/hub.c:570
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff816a73c0-ffffffff816a74ef: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817127a0)
Location: drivers/usb/core/hub.c:570
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817127a0-ffffffff817128cf: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81751450)
Location: drivers/usb/core/hub.c:573
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81751450-ffffffff81751585: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817758b0)
Location: drivers/usb/core/hub.c:574
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817758b0-ffffffff817759e5: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:576
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817b39a0-ffffffff817b3ab6: hub_ext_port_status (STB_LOCAL)
ffffffff817ba17d-ffffffff817ba1ad: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817e40d0-ffffffff817e41e6: hub_ext_port_status (STB_LOCAL)
ffffffff817ea9cd-ffffffff817ea9fd: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:580
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:wait_for_connected
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff818b2ab0-ffffffff818b2bbc: hub_ext_port_status (STB_LOCAL)
ffffffff818b9e33-ffffffff818b9e67: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:580
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:wait_for_connected
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff818c1420-ffffffff818c152c: hub_ext_port_status (STB_LOCAL)
ffffffff81c1a959-ffffffff81c1a98d: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:587
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff818a4700-ffffffff818a480c: hub_ext_port_status (STB_LOCAL)
ffffffff81c0c79f-ffffffff81c0c7d3: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:587
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff819393b0-ffffffff819394bc: hub_ext_port_status (STB_LOCAL)
ffffffff81d1373c-ffffffff81d13770: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:587
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81a90e70-ffffffff81a90f87: hub_ext_port_status (STB_LOCAL)
ffffffff81ede4ac-ffffffff81ede4dc: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c126f0)
Location: drivers/usb/core/hub.c:591
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81c126f0-ffffffff81c1282b: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c79560)
Location: drivers/usb/core/hub.c:591
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81c79560-ffffffff81c7969b: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2df60)
Location: drivers/usb/core/hub.c:611
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81d2df60-ffffffff81d2e09b: hub_ext_port_status (STB_LOCAL)
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
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a124d8)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffff800010a124d8-ffff800010a1266c: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeae88)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
c0aeae88-c0aeafec: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000aca6f0)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
c000000000aca6f0-c000000000aca8e8: hub_ext_port_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063854a)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffe00063854a-ffffffe0006386d4: hub_ext_port_status (STB_LOCAL)
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
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff8179c4b0-ffffffff8179c5c6: hub_ext_port_status (STB_LOCAL)
ffffffff817a2dad-ffffffff817a2ddd: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff8178e140-ffffffff8178e256: hub_ext_port_status (STB_LOCAL)
ffffffff81794bed-ffffffff81794c1d: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817d8f50-ffffffff817d9066: hub_ext_port_status (STB_LOCAL)
ffffffff817df84d-ffffffff817df87d: hub_ext_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hub_ext_port_status(struct usb_hub *hub, int port1, int type, u16 *status, u16 *change, u32 *ext_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:578
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:hub_port_debounce
  - drivers/usb/core/hub.c:hub_suspend
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817f32c0-ffffffff817f33d6: hub_ext_port_status (STB_LOCAL)
ffffffff817f9b3d-ffffffff817f9b6d: hub_ext_port_status.cold (STB_LOCAL)
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
