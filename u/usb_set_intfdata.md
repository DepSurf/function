# Function: <code>usb_set_intfdata</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8160848b)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_disconnect
  - drivers/usb/core/hub.c:hub_probe
```
```
In drivers/usb/core/driver.c (ffffffff81613a7b)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81619aa5)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8166ba80)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81673a56)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81679cc5)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816997b7)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff816a16e6)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff816a79a5)
Location: include/linux/usb.h:199
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816aeaad)
Location: include/linux/usb.h:269
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff816b67d7)
Location: include/linux/usb.h:269
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff816bcb55)
Location: include/linux/usb.h:269
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8171a094)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81722067)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81728525)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81758e4a)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81760daa)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81767375)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff8177d3ba)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff8178536a)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff8178b905)
Location: include/linux/usb.h:270
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817bb955)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817c3901)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817c9f29)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817ec163)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817f4281)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817faa49)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff818bb77a)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff818c3de1)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff818cace9)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1c2a3)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff818cfcd1)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff818d5dd9)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c0e189)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff818b3301)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff818b9319)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d15263)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81948751)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff8194edf9)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81edfe01)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81aa1251)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81aa7eb9)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c1cc4b)
Location: include/linux/usb.h:280
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81c268d1)
Location: include/linux/usb.h:280
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81c2eea5)
Location: include/linux/usb.h:280
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81c83b4f)
Location: include/linux/usb.h:292
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81c8d891)
Location: include/linux/usb.h:292
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81c96105)
Location: include/linux/usb.h:292
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81d3852e)
Location: include/linux/usb.h:291
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81d423c1)
Location: include/linux/usb.h:291
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81d4abe5)
Location: include/linux/usb.h:291
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a1a2a4)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffff800010a24d0c)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffff800010a2cd2c)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0af24fc)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (c0afb364)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (c0b01b00)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000ad3a24)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (c000000000adfb5c)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (c000000000ae9410)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe00063ecfe)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffe000647034)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffe00064d4a4)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817a4543)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817ac661)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817b2e29)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817960b4)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff8179e061)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817a4859)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817e0fe3)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff817e9101)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff817ef8c9)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817fb2d3)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_disconnect
```
```
In drivers/usb/core/driver.c (ffffffff81803631)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/usb/core/devio.c (ffffffff81809b09)
Location: include/linux/usb.h:268
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:driver_disconnect
```
</details>
</li>
</ul>

## Differences
