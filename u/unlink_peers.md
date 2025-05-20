# Function: <code>unlink_peers</code>

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
In drivers/usb/core/port.c (ffffffff8161f69f)
Location: drivers/usb/core/port.c:275
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff8168004f)
Location: drivers/usb/core/port.c:356
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff816add8f)
Location: drivers/usb/core/port.c:356
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff816c2f0f)
Location: drivers/usb/core/port.c:356
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff8172ecdf)
Location: drivers/usb/core/port.c:347
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff8176ddff)
Location: drivers/usb/core/port.c:380
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff8179247f)
Location: drivers/usb/core/port.c:390
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff817d0dc9)
Location: drivers/usb/core/port.c:399
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff81801cc9)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unlink_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818d1ef0)
Location: drivers/usb/core/port.c:405
Inline: False
Direct callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
```
**Symbols:**

```
ffffffff818d1ef0-ffffffff818d1fe5: unlink_peers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unlink_peers(struct usb_port *left, struct usb_port *right);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/port.c (ffffffff818dc2d0)
Location: drivers/usb/core/port.c:405
Inline: False
Direct callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
```
**Symbols:**

```
ffffffff818dc2d0-ffffffff818dc3c5: unlink_peers (STB_LOCAL)
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
In drivers/usb/core/port.c (ffffffff818bfb99)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff81956209)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff81aafd99)
Location: drivers/usb/core/port.c:406
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff81c37de9)
Location: drivers/usb/core/port.c:517
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff81c9f197)
Location: drivers/usb/core/port.c:528
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff81d53de7)
Location: drivers/usb/core/port.c:528
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffff800010a3613c)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (c0b09634)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (c000000000af42bc)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffe000653648)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff817ba0a9)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff817abad9)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff817f6b49)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
In drivers/usb/core/port.c (ffffffff81810d89)
Location: drivers/usb/core/port.c:405
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_remove_port_device
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
