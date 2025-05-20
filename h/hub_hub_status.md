# Function: <code>hub_hub_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81604420)
Location: drivers/usb/core/hub.c:871
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81604420-ffffffff81604508: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81664110)
Location: drivers/usb/core/hub.c:873
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81664110-ffffffff816641f8: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81692050)
Location: drivers/usb/core/hub.c:876
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81692050-ffffffff81692138: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a74f0)
Location: drivers/usb/core/hub.c:885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff816a74f0-ffffffff816a75d1: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817128d0)
Location: drivers/usb/core/hub.c:885
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff817128d0-ffffffff817129b1: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81751590)
Location: drivers/usb/core/hub.c:893
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81751590-ffffffff8175166e: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817759f0)
Location: drivers/usb/core/hub.c:894
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817759f0-ffffffff81775ace: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:921
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817b3ac0-ffffffff817b3b8f: hub_hub_status (STB_LOCAL)
ffffffff817ba1ad-ffffffff817ba1cb: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817e41f0-ffffffff817e42bf: hub_hub_status (STB_LOCAL)
ffffffff817ea9fd-ffffffff817eaa1b: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:925
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff818b2ca0-ffffffff818b2d66: hub_hub_status (STB_LOCAL)
ffffffff818b9e67-ffffffff818b9e8b: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:925
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff818c1610-ffffffff818c16d6: hub_hub_status (STB_LOCAL)
ffffffff81c1a98d-ffffffff81c1a9b1: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:932
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff818a4810-ffffffff818a48d6: hub_hub_status (STB_LOCAL)
ffffffff81c0c7d3-ffffffff81c0c7f7: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:932
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff819394c0-ffffffff81939586: hub_hub_status (STB_LOCAL)
ffffffff81d13770-ffffffff81d13794: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:932
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81a90f90-ffffffff81a91068: hub_hub_status (STB_LOCAL)
ffffffff81ede4dc-ffffffff81ede500: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c12840)
Location: drivers/usb/core/hub.c:936
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81c12840-ffffffff81c12933: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c796b0)
Location: drivers/usb/core/hub.c:936
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81c796b0-ffffffff81c797a3: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2e0b0)
Location: drivers/usb/core/hub.c:956
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
ffffffff81d2e0b0-ffffffff81d2e1a3: hub_hub_status (STB_LOCAL)
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
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a12670)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffff800010a12670-ffff800010a1278c: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeafec)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_configure
```
**Symbols:**

```
c0aeafec-c0aeb0e4: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000aca8f0)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
c000000000aca8f0-c000000000acaa5c: hub_hub_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe0006386d4)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffe0006386d4-ffffffe0006387ea: hub_hub_status (STB_LOCAL)
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
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff8179c5d0-ffffffff8179c69f: hub_hub_status (STB_LOCAL)
ffffffff817a2ddd-ffffffff817a2dfb: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff8178e260-ffffffff8178e32f: hub_hub_status (STB_LOCAL)
ffffffff81794c1d-ffffffff81794c3b: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817d9070-ffffffff817d913f: hub_hub_status (STB_LOCAL)
ffffffff817df87d-ffffffff817df89b: hub_hub_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hub_hub_status(struct usb_hub *hub, u16 *status, u16 *change);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:923
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff817f33e0-ffffffff817f34af: hub_hub_status (STB_LOCAL)
ffffffff817f9b6d-ffffffff817f9b8b: hub_hub_status.cold (STB_LOCAL)
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
