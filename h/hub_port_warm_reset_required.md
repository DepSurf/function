# Function: <code>hub_port_warm_reset_required</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81604a50)
Location: drivers/usb/core/hub.c:2697
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
```
**Symbols:**

```
ffffffff81604a50-ffffffff81604a94: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81664760)
Location: drivers/usb/core/hub.c:2694
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81664760-ffffffff8166479e: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81692280)
Location: drivers/usb/core/hub.c:2613
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81692280-ffffffff816922be: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a7be0)
Location: drivers/usb/core/hub.c:2641
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff816a7be0-ffffffff816a7c1e: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81712db0)
Location: drivers/usb/core/hub.c:2641
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:hub_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81712db0-ffffffff81712dee: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81751a90)
Location: drivers/usb/core/hub.c:2673
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81751a90-ffffffff81751acd: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81776010)
Location: drivers/usb/core/hub.c:2686
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
```
**Symbols:**

```
ffffffff81776010-ffffffff8177604d: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817b3e40)
Location: drivers/usb/core/hub.c:2726
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817b3e40-ffffffff817b3e7c: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e4570)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817e4570-ffffffff817e45ac: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b38d0)
Location: drivers/usb/core/hub.c:2742
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff818b38d0-ffffffff818b390e: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c2240)
Location: drivers/usb/core/hub.c:2760
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff818c2240-ffffffff818c227e: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a4ef0)
Location: drivers/usb/core/hub.c:2815
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff818a4ef0-ffffffff818a4f2e: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81939b90)
Location: drivers/usb/core/hub.c:2819
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81939b90-ffffffff81939bce: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a91460)
Location: drivers/usb/core/hub.c:2821
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81a91460-ffffffff81a914a8: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c16263)
Location: drivers/usb/core/hub.c:2830
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81c133d0-ffffffff81c13407: hub_port_warm_reset_required.part.0 (STB_LOCAL)
ffffffff81c13bf0-ffffffff81c13c38: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7d092)
Location: drivers/usb/core/hub.c:2850
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81c7a390-ffffffff81c7a3c7: hub_port_warm_reset_required.part.0 (STB_LOCAL)
ffffffff81c7aa00-ffffffff81c7aa48: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d31c52)
Location: drivers/usb/core/hub.c:2854
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_reset
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:check_port_resume_type
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_wait_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff81d2ed90-ffffffff81d2edc7: hub_port_warm_reset_required.part.0 (STB_LOCAL)
ffffffff81d2f630-ffffffff81d2f678: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a12840)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffff800010a12840-ffff800010a128d4: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeb3b8)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
c0aeb3b8-c0aeb430: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000acaef0)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
c000000000acaef0-c000000000acaf58: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000638ae2)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffe000638ae2-ffffffe000638b60: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8179c950)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff8179c950-ffffffff8179c98c: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8178e5e0)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff8178e5e0-ffffffff8178e61c: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817d93f0)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817d93f0-ffffffff817d942c: hub_port_warm_reset_required (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool hub_port_warm_reset_required(struct usb_hub *hub, int port1, u16 portstatus);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817f3760)
Location: drivers/usb/core/hub.c:2737
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/hub.c:usb_port_resume
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_port_reset
  - drivers/usb/core/hub.c:hub_activate
```
**Symbols:**

```
ffffffff817f3760-ffffffff817f379c: hub_port_warm_reset_required (STB_LOCAL)
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
