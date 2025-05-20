# Function: <code>hub_handle_remote_wakeup</code>

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
In drivers/usb/core/hub.c (ffffffff8160a769)
Location: drivers/usb/core/hub.c:3553
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
In drivers/usb/core/hub.c (ffffffff8166a2f2)
Location: drivers/usb/core/hub.c:3554
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
In drivers/usb/core/hub.c (ffffffff81698022)
Location: drivers/usb/core/hub.c:3480
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
In drivers/usb/core/hub.c (ffffffff816ad187)
Location: drivers/usb/core/hub.c:3499
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
In drivers/usb/core/hub.c (ffffffff81718917)
Location: drivers/usb/core/hub.c:3502
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
In drivers/usb/core/hub.c (ffffffff8175756e)
Location: drivers/usb/core/hub.c:3553
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
In drivers/usb/core/hub.c (ffffffff8177b9a9)
Location: drivers/usb/core/hub.c:3573
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
In drivers/usb/core/hub.c (ffffffff817b930d)
Location: drivers/usb/core/hub.c:3614
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
In drivers/usb/core/hub.c (ffffffff817e9b5d)
Location: drivers/usb/core/hub.c:3662
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
int hub_handle_remote_wakeup(struct usb_hub *hub, unsigned int port, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818b81f0)
Location: drivers/usb/core/hub.c:3676
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff818b81f0-ffffffff818b831f: hub_handle_remote_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hub_handle_remote_wakeup(struct usb_hub *hub, unsigned int port, u16 portstatus, u16 portchange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818c6b00)
Location: drivers/usb/core/hub.c:3694
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:port_event
```
**Symbols:**

```
ffffffff818c6b00-ffffffff818c6c2f: hub_handle_remote_wakeup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818aaf1e)
Location: drivers/usb/core/hub.c:3770
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8193fe9e)
Location: drivers/usb/core/hub.c:3774
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81a97fdb)
Location: drivers/usb/core/hub.c:3780
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1ae0e)
Location: drivers/usb/core/hub.c:3795
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c81d3d)
Location: drivers/usb/core/hub.c:3815
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d3667d)
Location: drivers/usb/core/hub.c:3817
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:port_event
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
In drivers/usb/core/hub.c (ffff800010a193b0)
Location: drivers/usb/core/hub.c:3662
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
In drivers/usb/core/hub.c (c0af1574)
Location: drivers/usb/core/hub.c:3662
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
In drivers/usb/core/hub.c (c000000000ad27cc)
Location: drivers/usb/core/hub.c:3662
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
In drivers/usb/core/hub.c (ffffffe00063df26)
Location: drivers/usb/core/hub.c:3662
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
In drivers/usb/core/hub.c (ffffffff817a1f3d)
Location: drivers/usb/core/hub.c:3662
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
In drivers/usb/core/hub.c (ffffffff81793d7d)
Location: drivers/usb/core/hub.c:3662
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
In drivers/usb/core/hub.c (ffffffff817de9dd)
Location: drivers/usb/core/hub.c:3662
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
In drivers/usb/core/hub.c (ffffffff817f8ccd)
Location: drivers/usb/core/hub.c:3662
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
</ul>
