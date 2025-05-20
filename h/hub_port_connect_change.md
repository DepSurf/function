# Function: <code>hub_port_connect_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8160a9a0)
Location: drivers/usb/core/hub.c:4931
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8166a5c2)
Location: drivers/usb/core/hub.c:4949
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816982f2)
Location: drivers/usb/core/hub.c:4926
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816ad3cd)
Location: drivers/usb/core/hub.c:4947
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8171873e)
Location: drivers/usb/core/hub.c:4985
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817577d0)
Location: drivers/usb/core/hub.c:5055
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177bd42)
Location: drivers/usb/core/hub.c:5117
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b964d)
Location: drivers/usb/core/hub.c:5164
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e9e9d)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hub_port_connect_change(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b8d00)
Location: drivers/usb/core/hub.c:5308
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff818b8d00-ffffffff818b9054: hub_port_connect_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hub_port_connect_change(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c75f0)
Location: drivers/usb/core/hub.c:5323
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff818c75f0-ffffffff818c7934: hub_port_connect_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hub_port_connect_change(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818aaa30)
Location: drivers/usb/core/hub.c:5447
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff818aaa30-ffffffff818aad92: hub_port_connect_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hub_port_connect_change(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193f970)
Location: drivers/usb/core/hub.c:5460
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff8193f970-ffffffff8193fd14: hub_port_connect_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hub_port_connect_change(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a97ad0)
Location: drivers/usb/core/hub.c:5467
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff81a97ad0-ffffffff81a97e58: hub_port_connect_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hub_port_connect_change(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1a8f0)
Location: drivers/usb/core/hub.c:5477
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff81c1a8f0-ffffffff81c1ac6c: hub_port_connect_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hub_port_connect_change(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c81900)
Location: drivers/usb/core/hub.c:5552
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff81c81900-ffffffff81c81b9f: hub_port_connect_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hub_port_connect_change(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d36230)
Location: drivers/usb/core/hub.c:5553
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff81d36230-ffffffff81d364dc: hub_port_connect_change (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a196cc)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0af1848)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad2884)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063e188)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817a227d)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817940bd)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817ded1d)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f900d)
Location: drivers/usb/core/hub.c:5209
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
