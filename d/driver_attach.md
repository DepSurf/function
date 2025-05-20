# Function: <code>driver_attach</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8154b4b0)
Location: drivers/base/dd.c:659
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:driver_attach_async
  - drivers/base/bus.c:bus_add_driver
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff8154b4b0-ffffffff8154b4d0: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8159d1a0)
Location: drivers/base/dd.c:749
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:driver_attach_async
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff8159d1a0-ffffffff8159d1c0: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815cb6e0)
Location: drivers/base/dd.c:773
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:driver_attach_async
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff815cb6e0-ffffffff815cb700: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff815e02b0)
Location: drivers/base/dd.c:780
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:driver_attach_async
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff815e02b0-ffffffff815e02d0: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81647370)
Location: drivers/base/dd.c:817
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:driver_attach_async
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff81647370-ffffffff81647390: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81682860)
Location: drivers/base/dd.c:831
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:driver_attach_async
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff81682860-ffffffff81682880: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816a23a0)
Location: drivers/base/dd.c:918
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/base/bus.c:driver_attach_async
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff816a23a0-ffffffff816a23c0: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816db0e0)
Location: drivers/base/dd.c:1074
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff816db0e0-ffffffff816db100: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816ff0b0)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff816ff0b0-ffffffff816ff0d0: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b8cc0)
Location: drivers/base/dd.c:1063
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff817b8cc0-ffffffff817b8ce0: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817cda30)
Location: drivers/base/dd.c:1109
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff817cda30-ffffffff817cda50: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff817b13b0)
Location: drivers/base/dd.c:1131
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff817b13b0-ffffffff817b13d0: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8183a5f0)
Location: drivers/base/dd.c:1158
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff8183a5f0-ffffffff8183a610: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8197cd50)
Location: drivers/base/dd.c:1181
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff8197cd50-ffffffff8197cd7c: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81ae9f80)
Location: drivers/base/dd.c:1209
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff81ae9f80-ffffffff81ae9fac: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b38300)
Location: drivers/base/dd.c:1231
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff81b38300-ffffffff81b3832c: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff81b8fda0)
Location: drivers/base/dd.c:1231
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff81b8fda0-ffffffff81b8fdcc: driver_attach (STB_GLOBAL)
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
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffff8000108ea0e8)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffff8000108ea0e8-ffff8000108ea124: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c09d8128)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
c09d8128-c09d8158: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (c0000000009810b0)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
c0000000009810b0-c0000000009810f8: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffe00057df82)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffe00057df82-ffffffe00057dfb8: driver_attach (STB_GLOBAL)
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
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816c48a0)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff816c48a0-ffffffff816c48c0: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8169fb20)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
  - drivers/hv/vmbus_drv.c:new_id_store
```
**Symbols:**

```
ffffffff8169fb20-ffffffff8169fb40: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff816f2d70)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff816f2d70-ffffffff816f2d90: driver_attach (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int driver_attach(struct device_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/dd.c (ffffffff8170d5a0)
Location: drivers/base/dd.c:1089
Inline: False
Direct callers:
  - drivers/pci/pci-driver.c:pci_add_dynid
  - drivers/char/agp/amd64-agp.c:agp_amd64_init
  - drivers/base/bus.c:bus_add_driver
  - drivers/dax/bus.c:do_id_store
  - drivers/usb/core/driver.c:usb_store_new_id
  - drivers/input/serio/serio.c:serio_handle_event
```
**Symbols:**

```
ffffffff8170d5a0-ffffffff8170d5c0: driver_attach (STB_GLOBAL)
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
