# Function: <code>device_bind_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8154b8e0)
Location: drivers/base/dd.c:264
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8154b8e0-ffffffff8154b90f: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8159d5e0)
Location: drivers/base/dd.c:311
Inline: False
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8159d5e0-ffffffff8159d63a: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815cb960)
Location: drivers/base/dd.c:307
Inline: False
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff815cb960-ffffffff815cb9ba: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815e0530)
Location: drivers/base/dd.c:308
Inline: False
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff815e0530-ffffffff815e058a: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81647600)
Location: drivers/base/dd.c:336
Inline: False
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81647600-ffffffff8164765a: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81682af0)
Location: drivers/base/dd.c:358
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81682af0-ffffffff81682b4a: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a2730)
Location: drivers/base/dd.c:423
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816a2730-ffffffff816a278a: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816db4e0)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816db4e0-ffffffff816db53b: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816ff4b0)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816ff4b0-ffffffff816ff50b: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b98cc)
Location: drivers/base/dd.c:435
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:serio_bind_driver
```
**Symbols:**

```
ffffffff817b9300-ffffffff817b935b: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817ce8fc)
Location: drivers/base/dd.c:458
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:serio_bind_driver
```
**Symbols:**

```
ffffffff817ce0b0-ffffffff817ce10b: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b22fc)
Location: drivers/base/dd.c:475
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff817b1a40-ffffffff817b1aa3: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8183b6e8)
Location: drivers/base/dd.c:477
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8183ad00-ffffffff8183ad63: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8197dc82)
Location: drivers/base/dd.c:491
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8197d2d0-ffffffff8197d343: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81aeb502)
Location: drivers/base/dd.c:496
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81aea6d0-ffffffff81aea743: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b397f9)
Location: drivers/base/dd.c:495
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81b38a40-ffffffff81b38a98: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b912b9)
Location: drivers/base/dd.c:495
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff81b90500-ffffffff81b90558: device_bind_driver (STB_GLOBAL)
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
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108ea5c0)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffff8000108ea5c0-ffff8000108ea62c: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d8690)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
c09d8690-c09d86ec: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c000000000981730)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
c000000000981730-c0000000009817d4: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057e412)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffe00057e412-ffffffe00057e474: device_bind_driver (STB_GLOBAL)
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
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c4ca0)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816c4ca0-ffffffff816c4cfb: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8169ff20)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8169ff20-ffffffff8169ff7b: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f3170)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff816f3170-ffffffff816f31cb: device_bind_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int device_bind_driver(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170d9a0)
Location: drivers/base/dd.c:466
Inline: True
Direct callers:
  - drivers/pnp/card.c:pnp_request_card_device
  - drivers/base/dd.c:__device_attach
  - drivers/net/phy/phy_device.c:phy_attach_direct
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/input/serio/serio.c:drvctl_store
```
**Symbols:**

```
ffffffff8170d9a0-ffffffff8170d9fb: device_bind_driver (STB_GLOBAL)
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
