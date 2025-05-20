# Function: <code>port_event</code>

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
In drivers/usb/core/hub.c (ffffffff8160a5e0)
Location: drivers/usb/core/hub.c:4984
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
In drivers/usb/core/hub.c (ffffffff8166a162)
Location: drivers/usb/core/hub.c:5002
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
In drivers/usb/core/hub.c (ffffffff81697e92)
Location: drivers/usb/core/hub.c:4979
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816ad020)
Location: drivers/usb/core/hub.c:5000
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff816ad020-ffffffff816ad6cd: port_event (STB_LOCAL)
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
Location: drivers/usb/core/hub.c:5038
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817573e0)
Location: drivers/usb/core/hub.c:5108
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817573e0-ffffffff81757aa2: port_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177b880)
Location: drivers/usb/core/hub.c:5207
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff8177b880-ffffffff8177c014: port_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5254
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817b91e0-ffffffff817b9958: port_event (STB_LOCAL)
ffffffff817bac70-ffffffff817bacca: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817e9a30-ffffffff817ea1a8: port_event (STB_LOCAL)
ffffffff817eb493-ffffffff817eb4ed: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5423
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff818b9060-ffffffff818b954f: port_event (STB_LOCAL)
ffffffff818baab3-ffffffff818bab0c: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5438
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff818c7940-ffffffff818c7e2f: port_event (STB_LOCAL)
ffffffff81c1b5dc-ffffffff81c1b635: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5562
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff818aada0-ffffffff818ab495: port_event (STB_LOCAL)
ffffffff81c0d4bb-ffffffff81c0d511: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5575
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff8193fd20-ffffffff81940415: port_event (STB_LOCAL)
ffffffff81d144fe-ffffffff81d14554: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5580
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81a97e60-ffffffff81a985d3: port_event (STB_LOCAL)
ffffffff81edf05e-ffffffff81edf0b8: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1ac80)
Location: drivers/usb/core/hub.c:5590
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81c1ac80-ffffffff81c1b489: port_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c81bb0)
Location: drivers/usb/core/hub.c:5661
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81c81bb0-ffffffff81c823b8: port_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d364f0)
Location: drivers/usb/core/hub.c:5662
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81d364f0-ffffffff81d36cf8: port_event (STB_LOCAL)
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
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a19208)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffff800010a19208-ffff800010a199d0: port_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0af13b0)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
c0af13b0-c0af1c24: port_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad25e0)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
c000000000ad25e0-c000000000ad2f18: port_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063ddba)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffe00063ddba-ffffffe00063e4fa: port_event (STB_LOCAL)
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
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817a1e10-ffffffff817a2588: port_event (STB_LOCAL)
ffffffff817a3873-ffffffff817a38cd: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81793c50-ffffffff817943c8: port_event (STB_LOCAL)
ffffffff817953e4-ffffffff8179543e: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817de8b0-ffffffff817df028: port_event (STB_LOCAL)
ffffffff817e0313-ffffffff817e036d: port_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void port_event(struct usb_hub *hub, int port1);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:5299
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817f8ba0-ffffffff817f9318: port_event (STB_LOCAL)
ffffffff817fa603-ffffffff817fa65d: port_event.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
