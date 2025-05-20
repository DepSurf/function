# Function: <code>hub_port_connect</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816099f0)
Location: drivers/usb/core/hub.c:4711
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff816099f0-ffffffff8160a3a8: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81669550)
Location: drivers/usb/core/hub.c:4729
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81669550-ffffffff81669f13: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81697280)
Location: drivers/usb/core/hub.c:4706
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81697280-ffffffff81697c43: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816ac630)
Location: drivers/usb/core/hub.c:4725
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff816ac630-ffffffff816ad018: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81717ae0)
Location: drivers/usb/core/hub.c:4754
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81717ae0-ffffffff81718563: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81756980)
Location: drivers/usb/core/hub.c:4824
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff81756980-ffffffff817573d5: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177ae20)
Location: drivers/usb/core/hub.c:4886
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff8177ae20-ffffffff8177b875: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4933
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff817b8990-ffffffff817b91dd: hub_port_connect (STB_LOCAL)
ffffffff817baacc-ffffffff817bac70: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff817e91e0-ffffffff817e9a2d: hub_port_connect (STB_LOCAL)
ffffffff817eb346-ffffffff817eb493: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5080
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff818b8500-ffffffff818b8cfb: hub_port_connect (STB_LOCAL)
ffffffff818ba960-ffffffff818baab3: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5095
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff818c6e00-ffffffff818c75e5: hub_port_connect (STB_LOCAL)
ffffffff81c1b486-ffffffff81c1b5dc: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5219
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff818aa1a0-ffffffff818aaa25: hub_port_connect (STB_LOCAL)
ffffffff81c0d367-ffffffff81c0d4bb: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5220
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff8193f090-ffffffff8193f970: hub_port_connect (STB_LOCAL)
ffffffff81d14361-ffffffff81d144fe: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5227
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81a97120-ffffffff81a97ac3: hub_port_connect (STB_LOCAL)
ffffffff81edeeb0-ffffffff81edf05e: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c19cc0)
Location: drivers/usb/core/hub.c:5229
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81c19cc0-ffffffff81c1a8de: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c80ce0)
Location: drivers/usb/core/hub.c:5304
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81c80ce0-ffffffff81c818ec: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d356b0)
Location: drivers/usb/core/hub.c:5306
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_connect_change
```
**Symbols:**

```
ffffffff81d356b0-ffffffff81d36217: hub_port_connect (STB_LOCAL)
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
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a18808)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffff800010a18808-ffff800010a19204: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0af09f0)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
c0af09f0-c0af13b0: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad1950)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
c000000000ad1950-c000000000ad25d4: hub_port_connect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063d510)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffe00063d510-ffffffe00063ddba: hub_port_connect (STB_LOCAL)
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
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff817a15c0-ffffffff817a1e0d: hub_port_connect (STB_LOCAL)
ffffffff817a3726-ffffffff817a3873: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff81793400-ffffffff81793c41: hub_port_connect (STB_LOCAL)
ffffffff81795297-ffffffff817953e4: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff817de060-ffffffff817de8ad: hub_port_connect (STB_LOCAL)
ffffffff817e01c6-ffffffff817e0313: hub_port_connect.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void hub_port_connect(struct usb_hub *hub, int port1, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4981
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff817f8330-ffffffff817f8b9b: hub_port_connect (STB_LOCAL)
ffffffff817fa4b6-ffffffff817fa603: hub_port_connect.cold (STB_LOCAL)
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
