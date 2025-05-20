# Function: <code>hub_port_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81606040)
Location: drivers/usb/core/hub.c:4327
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81606040-ffffffff81606bc3: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81665da0)
Location: drivers/usb/core/hub.c:4339
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81665da0-ffffffff81666933: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81693830)
Location: drivers/usb/core/hub.c:4316
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81693830-ffffffff816943d0: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff816a8f20)
Location: drivers/usb/core/hub.c:4335
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff816a8f20-ffffffff816a9ad8: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81714340)
Location: drivers/usb/core/hub.c:4351
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81714340-ffffffff81714f27: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff817530f0)
Location: drivers/usb/core/hub.c:4402
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff817530f0-ffffffff81753d70: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffff81777550)
Location: drivers/usb/core/hub.c:4464
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81777550-ffffffff817781ec: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4511
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff817b5570-ffffffff817b6103: hub_port_init (STB_LOCAL)
ffffffff817ba3ac-ffffffff817ba5a7: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff817e5ca0-ffffffff817e6833: hub_port_init (STB_LOCAL)
ffffffff817eabfc-ffffffff817eadf5: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4573
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff818b5bb0-ffffffff818b6588: hub_port_init (STB_LOCAL)
ffffffff818ba102-ffffffff818ba2cb: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4591
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff818c4500-ffffffff818c4ec9: hub_port_init (STB_LOCAL)
ffffffff81c1ac28-ffffffff81c1adf9: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4711
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff818a7780-ffffffff818a81af: hub_port_init (STB_LOCAL)
ffffffff81c0ca6e-ffffffff81c0cc67: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4715
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff8193c610-ffffffff8193d018: hub_port_init (STB_LOCAL)
ffffffff81d139f1-ffffffff81d13c17: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4721
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81a94380-ffffffff81a94d48: hub_port_init (STB_LOCAL)
ffffffff81ede789-ffffffff81ede9c1: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4717
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81c166e0-ffffffff81c172ac: hub_port_init (STB_LOCAL)
ffffffff8209e776-ffffffff8209e7a0: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter, struct usb_device_descriptor *dev_descr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4805
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81c7d4f0-ffffffff81c7e2d5: hub_port_init (STB_LOCAL)
ffffffff8211fce1-ffffffff8211fd33: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter, struct usb_device_descriptor *dev_descr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4819
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff81d320a0-ffffffff81d32ca7: hub_port_init (STB_LOCAL)
ffffffff822014c7-ffffffff82201509: hub_port_init.cold (STB_LOCAL)
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
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffff800010a14b28)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffff800010a14b28-ffff800010a1569c: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c0aeccf0)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
c0aeccf0-c0aed9d0: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (c000000000accbb0)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
c000000000accbb0-c000000000acdaf4: hub_port_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/core/hub.c (ffffffe000639c1e)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffe000639c1e-ffffffe00063a70c: hub_port_init (STB_LOCAL)
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
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff8179e080-ffffffff8179ec13: hub_port_init (STB_LOCAL)
ffffffff817a2fdc-ffffffff817a31d5: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff8178fd00-ffffffff81790893: hub_port_init (STB_LOCAL)
ffffffff81794e1c-ffffffff81795015: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff817dab20-ffffffff817db6b3: hub_port_init (STB_LOCAL)
ffffffff817dfa7c-ffffffff817dfc75: hub_port_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int hub_port_init(struct usb_hub *hub, struct usb_device *udev, int port1, int retry_counter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/core/hub.c (0)
Location: drivers/usb/core/hub.c:4559
Inline: False
Direct callers:
  - drivers/usb/core/hub.c:usb_reset_and_verify_device
  - drivers/usb/core/hub.c:hub_port_connect
```
**Symbols:**

```
ffffffff817f4db0-ffffffff817f5943: hub_port_init (STB_LOCAL)
ffffffff817f9d6c-ffffffff817f9f65: hub_port_init.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct usb_device_descriptor *dev_descr</code>
</li>
</ul>
</details>
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
