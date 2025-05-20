# Function: <code>usb_submit_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff81610140)
Location: drivers/usb/core/urb.c:324
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_irq
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff81610140-ffffffff81610694: usb_submit_urb.part.6 (STB_LOCAL)
ffffffff816106a0-ffffffff8161070b: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8166fd10)
Location: drivers/usb/core/urb.c:324
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_irq
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8166fd10-ffffffff81670236: usb_submit_urb.part.6 (STB_LOCAL)
ffffffff81670240-ffffffff816702aa: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8169d9e0)
Location: drivers/usb/core/urb.c:327
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_irq
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8169d9e0-ffffffff8169df0c: usb_submit_urb.part.8 (STB_LOCAL)
ffffffff8169df10-ffffffff8169df7a: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff816b2de0)
Location: drivers/usb/core/urb.c:327
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_irq
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff816b2de0-ffffffff816b3339: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8171e4a0)
Location: drivers/usb/core/urb.c:352
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_irq
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8171e4a0-ffffffff8171ea47: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8175cfc0)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_irq
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8175cfc0-ffffffff8175d55e: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817815f0)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_irq
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817815f0-ffffffff81781b98: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817bfb10)
Location: drivers/usb/core/urb.c:351
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817bfb10-ffffffff817c00e9: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817f0490)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817f0490-ffffffff817f0a69: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818bf9f0)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff818bf9f0-ffffffff818bff7f: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818cc5b0)
Location: drivers/usb/core/urb.c:367
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff818cc5b0-ffffffff818ccb72: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff818afbd0)
Location: drivers/usb/core/urb.c:367
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff818afbd0-ffffffff818b018d: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (0)
Location: drivers/usb/core/urb.c:367
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
**Symbols:**

```
ffffffff81d15eb3-ffffffff81d15f09: usb_submit_urb.cold (STB_LOCAL)
ffffffff81944d20-ffffffff819453e1: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (0)
Location: drivers/usb/core/urb.c:367
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
**Symbols:**

```
ffffffff81ee0a56-ffffffff81ee0aac: usb_submit_urb.cold (STB_LOCAL)
ffffffff81a9d380-ffffffff81a9da61: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (0)
Location: drivers/usb/core/urb.c:368
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
**Symbols:**

```
ffffffff8209e904-ffffffff8209e95a: usb_submit_urb.cold (STB_LOCAL)
ffffffff81c22450-ffffffff81c22b0c: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (0)
Location: drivers/usb/core/urb.c:368
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
**Symbols:**

```
ffffffff8211fe92-ffffffff8211fee8: usb_submit_urb.cold (STB_LOCAL)
ffffffff81c893c0-ffffffff81c89a8b: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/urb.c (0)
Location: drivers/usb/core/urb.c:368
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:usbfs_start_wait_urb
```
**Symbols:**

```
ffffffff82201668-ffffffff822016be: usb_submit_urb.cold (STB_LOCAL)
ffffffff81d3de10-ffffffff81d3e47a: usb_submit_urb (STB_GLOBAL)
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
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffff800010a20068)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffff800010a20068-ffff800010a205f4: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c0af7248)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
c0af7248-c0af77c4: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (c000000000ada300)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
c000000000ada300-c000000000adaa64: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffe0006433e4)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffe0006433e4-ffffffe0006438c4: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817a8870)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817a8870-ffffffff817a8e49: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff8179a280)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff8179a280-ffffffff8179a859: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817e5310)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817e5310-ffffffff817e58e9: usb_submit_urb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int usb_submit_urb(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/urb.c (ffffffff817ff570)
Location: drivers/usb/core/urb.c:352
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_activate
  - drivers/usb/core/hub.c:hub_resubmit_irq_urb
  - drivers/usb/core/message.c:usb_sg_wait
  - drivers/usb/core/message.c:usb_start_wait_urb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
```
**Symbols:**

```
ffffffff817ff570-ffffffff817ffb49: usb_submit_urb (STB_GLOBAL)
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
