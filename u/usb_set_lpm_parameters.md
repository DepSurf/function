# Function: <code>usb_set_lpm_parameters</code>

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
In drivers/usb/core/hub.c (ffffffff816067a7)
Location: drivers/usb/core/hub.c:292
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff81666559)
Location: drivers/usb/core/hub.c:294
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff81693fee)
Location: drivers/usb/core/hub.c:297
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff816a982a)
Location: drivers/usb/core/hub.c:297
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff81714c79)
Location: drivers/usb/core/hub.c:297
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff817538d4)
Location: drivers/usb/core/hub.c:300
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff81777d5e)
Location: drivers/usb/core/hub.c:301
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff817b5cf8)
Location: drivers/usb/core/hub.c:303
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff817e6428)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void usb_set_lpm_parameters(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b3570)
Location: drivers/usb/core/hub.c:307
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff818b3570-ffffffff818b3721: usb_set_lpm_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void usb_set_lpm_parameters(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c1ee0)
Location: drivers/usb/core/hub.c:307
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff818c1ee0-ffffffff818c2091: usb_set_lpm_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void usb_set_lpm_parameters(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818a5050)
Location: drivers/usb/core/hub.c:314
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff818a5050-ffffffff818a525f: usb_set_lpm_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void usb_set_lpm_parameters(struct usb_device *udev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81939cf0)
Location: drivers/usb/core/hub.c:314
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81939cf0-ffffffff81939eff: usb_set_lpm_parameters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a91890)
Location: drivers/usb/core/hub.c:314
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81a91890-ffffffff81a91ad3: usb_set_lpm_parameters.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c13990)
Location: drivers/usb/core/hub.c:318
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81c13990-ffffffff81c13bd3: usb_set_lpm_parameters.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c7a7a0)
Location: drivers/usb/core/hub.c:318
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81c7a7a0-ffffffff81c7a9e3: usb_set_lpm_parameters.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d2f3d0)
Location: drivers/usb/core/hub.c:334
Inline: True
Direct callers:
  - drivers/usb/core/hub.c:hub_port_init
```
**Symbols:**

```
ffffffff81d2f3d0-ffffffff81d2f61c: usb_set_lpm_parameters.constprop.0 (STB_LOCAL)
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
In drivers/usb/core/hub.c (ffff800010a15210)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (c0aed480)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (c000000000acd450)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffe00063a258)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff8179e808)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff81790488)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff817db2a8)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
In drivers/usb/core/hub.c (ffffffff817f5538)
Location: drivers/usb/core/hub.c:305
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_init
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
</ul>
