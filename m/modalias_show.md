# Function: <code>modalias_show</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8143b510)
Location: drivers/pci/pci-sysfs.c:157
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8145b7c0)
Location: drivers/rapidio/rio-sysfs.c:91
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff814beae0)
Location: drivers/virtio/virtio.c:35
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff814cef70)
Location: drivers/xen/xenbus/xenbus_probe.c:401
Inline: False
```
```
In drivers/base/platform.c (ffffffff8154e3f0)
Location: drivers/base/platform.c:810
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81597a90)
Location: drivers/nvdimm/bus.c:254
Inline: False
```
```
In drivers/spi/spi.c (ffffffff815e6550)
Location: drivers/spi/spi.c:57
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81618170)
Location: drivers/usb/core/sysfs.c:943
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81663a30)
Location: drivers/input/serio/serio.c:366
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff816ca8a0)
Location: drivers/mmc/core/sdio_bus.c:49
Inline: False
```
**Symbols:**

```
ffffffff8143b510-ffffffff8143b55f: modalias_show (STB_LOCAL)
ffffffff8145b7c0-ffffffff8145b7f1: modalias_show (STB_LOCAL)
ffffffff814beae0-ffffffff814beb0b: modalias_show (STB_LOCAL)
ffffffff814cef70-ffffffff814cef9d: modalias_show (STB_LOCAL)
ffffffff8154e3f0-ffffffff8154e448: modalias_show (STB_LOCAL)
ffffffff81597a90-ffffffff81597ab8: modalias_show (STB_LOCAL)
ffffffff815e6550-ffffffff815e659f: modalias_show (STB_LOCAL)
ffffffff81618170-ffffffff816181ed: modalias_show (STB_LOCAL)
ffffffff81663a30-ffffffff81663a6d: modalias_show (STB_LOCAL)
ffffffff816ca8a0-ffffffff816ca8d5: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81487390)
Location: drivers/pci/pci-sysfs.c:157
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814a9950)
Location: drivers/rapidio/rio-sysfs.c:91
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff8150e7f0)
Location: drivers/virtio/virtio.c:35
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8151fb70)
Location: drivers/xen/xenbus/xenbus_probe.c:401
Inline: False
```
```
In drivers/base/platform.c (ffffffff815a01f0)
Location: drivers/base/platform.c:830
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff815ecb90)
Location: drivers/nvdimm/bus.c:517
Inline: False
```
```
In drivers/spi/spi.c (ffffffff816443d0)
Location: drivers/spi/spi.c:57
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81678240)
Location: drivers/usb/core/sysfs.c:966
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff816c3c30)
Location: drivers/input/serio/serio.c:366
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8172d850)
Location: drivers/mmc/core/sdio_bus.c:49
Inline: False
```
**Symbols:**

```
ffffffff81487390-ffffffff814873df: modalias_show (STB_LOCAL)
ffffffff814a9950-ffffffff814a9981: modalias_show (STB_LOCAL)
ffffffff8150e7f0-ffffffff8150e81b: modalias_show (STB_LOCAL)
ffffffff8151fb70-ffffffff8151fb9d: modalias_show (STB_LOCAL)
ffffffff815a01f0-ffffffff815a0248: modalias_show (STB_LOCAL)
ffffffff815ecb90-ffffffff815ecbb8: modalias_show (STB_LOCAL)
ffffffff816443d0-ffffffff8164441f: modalias_show (STB_LOCAL)
ffffffff81678240-ffffffff816782bd: modalias_show (STB_LOCAL)
ffffffff816c3c30-ffffffff816c3c6d: modalias_show (STB_LOCAL)
ffffffff8172d850-ffffffff8172d885: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814a8b40)
Location: drivers/pci/pci-sysfs.c:158
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814cba60)
Location: drivers/rapidio/rio-sysfs.c:91
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff8153a950)
Location: drivers/virtio/virtio.c:35
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8154c020)
Location: drivers/xen/xenbus/xenbus_probe.c:401
Inline: False
```
```
In drivers/base/platform.c (ffffffff815ce830)
Location: drivers/base/platform.c:844
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81619980)
Location: drivers/nvdimm/bus.c:519
Inline: False
```
```
In drivers/spi/spi.c (ffffffff816754a0)
Location: drivers/spi/spi.c:58
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff816a5f20)
Location: drivers/usb/core/sysfs.c:983
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff816f1bf0)
Location: drivers/input/serio/serio.c:366
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81760810)
Location: drivers/mmc/core/sdio_bus.c:49
Inline: False
```
**Symbols:**

```
ffffffff814a8b40-ffffffff814a8b8f: modalias_show (STB_LOCAL)
ffffffff814cba60-ffffffff814cba91: modalias_show (STB_LOCAL)
ffffffff8153a950-ffffffff8153a97b: modalias_show (STB_LOCAL)
ffffffff8154c020-ffffffff8154c04d: modalias_show (STB_LOCAL)
ffffffff815ce830-ffffffff815ce888: modalias_show (STB_LOCAL)
ffffffff81619980-ffffffff816199a8: modalias_show (STB_LOCAL)
ffffffff816754a0-ffffffff816754ef: modalias_show (STB_LOCAL)
ffffffff816a5f20-ffffffff816a5f9d: modalias_show (STB_LOCAL)
ffffffff816f1bf0-ffffffff816f1c2d: modalias_show (STB_LOCAL)
ffffffff81760810-ffffffff81760845: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814b3100)
Location: drivers/pci/pci-sysfs.c:280
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff814d7f70)
Location: drivers/rapidio/rio-sysfs.c:91
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff8154e190)
Location: drivers/virtio/virtio.c:35
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81560270)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/base/platform.c (ffffffff815e32c0)
Location: drivers/base/platform.c:844
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff8162d980)
Location: drivers/nvdimm/bus.c:582
Inline: False
```
```
In drivers/spi/spi.c (ffffffff81689be0)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff816bb280)
Location: drivers/usb/core/sysfs.c:983
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817074e0)
Location: drivers/input/serio/serio.c:366
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8177ef60)
Location: drivers/mmc/core/sdio_bus.c:50
Inline: False
```
**Symbols:**

```
ffffffff814b3100-ffffffff814b3146: modalias_show (STB_LOCAL)
ffffffff814d7f70-ffffffff814d7fa4: modalias_show (STB_LOCAL)
ffffffff8154e190-ffffffff8154e1be: modalias_show (STB_LOCAL)
ffffffff81560270-ffffffff8156029d: modalias_show (STB_LOCAL)
ffffffff815e32c0-ffffffff815e3318: modalias_show (STB_LOCAL)
ffffffff8162d980-ffffffff8162d9a8: modalias_show (STB_LOCAL)
ffffffff81689be0-ffffffff81689c2f: modalias_show (STB_LOCAL)
ffffffff816bb280-ffffffff816bb2eb: modalias_show (STB_LOCAL)
ffffffff817074e0-ffffffff81707520: modalias_show (STB_LOCAL)
ffffffff8177ef60-ffffffff8177ef98: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff814f2810)
Location: drivers/pci/pci-sysfs.c:281
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81518150)
Location: drivers/rapidio/rio-sysfs.c:91
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff815b1880)
Location: drivers/virtio/virtio.c:35
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c4510)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff81609850)
Location: drivers/tty/serdev/core.c:281
Inline: False
```
```
In drivers/base/platform.c (ffffffff8164a470)
Location: drivers/base/platform.c:844
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81696140)
Location: drivers/nvdimm/bus.c:582
Inline: False
```
```
In drivers/spi/spi.c (ffffffff816f34a0)
Location: drivers/spi/spi.c:64
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81726c40)
Location: drivers/usb/core/sysfs.c:984
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817786c0)
Location: drivers/input/serio/serio.c:366
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff817f5500)
Location: drivers/mmc/core/sdio_bus.c:50
Inline: False
```
**Symbols:**

```
ffffffff814f2810-ffffffff814f2856: modalias_show (STB_LOCAL)
ffffffff81518150-ffffffff81518184: modalias_show (STB_LOCAL)
ffffffff815b1880-ffffffff815b18ae: modalias_show (STB_LOCAL)
ffffffff815c4510-ffffffff815c453d: modalias_show (STB_LOCAL)
ffffffff81609850-ffffffff8160986a: modalias_show (STB_LOCAL)
ffffffff8164a470-ffffffff8164a4c8: modalias_show (STB_LOCAL)
ffffffff81696140-ffffffff81696168: modalias_show (STB_LOCAL)
ffffffff816f34a0-ffffffff816f34ef: modalias_show (STB_LOCAL)
ffffffff81726c40-ffffffff81726cab: modalias_show (STB_LOCAL)
ffffffff817786c0-ffffffff81778700: modalias_show (STB_LOCAL)
ffffffff817f5500-ffffffff817f5538: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81522b20)
Location: drivers/pci/pci-sysfs.c:264
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8154dde0)
Location: drivers/rapidio/rio-sysfs.c:91
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff815e9cb0)
Location: drivers/virtio/virtio.c:35
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fcba0)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff816430d0)
Location: drivers/tty/serdev/core.c:22
Inline: False
```
```
In drivers/base/platform.c (ffffffff816859e0)
Location: drivers/base/platform.c:842
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff816d2230)
Location: drivers/nvdimm/bus.c:590
Inline: False
```
```
In drivers/spi/spi.c (ffffffff8172ff10)
Location: drivers/spi/spi.c:67
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81765aa0)
Location: drivers/usb/core/sysfs.c:1006
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817b9420)
Location: drivers/input/serio/serio.c:366
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8183e9e0)
Location: drivers/mmc/core/sdio_bus.c:50
Inline: False
```
**Symbols:**

```
ffffffff81522b20-ffffffff81522b66: modalias_show (STB_LOCAL)
ffffffff8154dde0-ffffffff8154de14: modalias_show (STB_LOCAL)
ffffffff815e9cb0-ffffffff815e9cde: modalias_show (STB_LOCAL)
ffffffff815fcba0-ffffffff815fcbcd: modalias_show (STB_LOCAL)
ffffffff816430d0-ffffffff816430ea: modalias_show (STB_LOCAL)
ffffffff816859e0-ffffffff81685a3a: modalias_show (STB_LOCAL)
ffffffff816d2230-ffffffff816d2258: modalias_show (STB_LOCAL)
ffffffff8172ff10-ffffffff8172ff5f: modalias_show (STB_LOCAL)
ffffffff81765aa0-ffffffff81765b0b: modalias_show (STB_LOCAL)
ffffffff817b9420-ffffffff817b9460: modalias_show (STB_LOCAL)
ffffffff8183e9e0-ffffffff8183ea18: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81538960)
Location: drivers/pci/pci-sysfs.c:263
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81565240)
Location: drivers/rapidio/rio-sysfs.c:91
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff816041c0)
Location: drivers/virtio/virtio.c:35
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81617c80)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff81661310)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (ffffffff816a5640)
Location: drivers/base/platform.c:844
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff816f3ac0)
Location: drivers/nvdimm/bus.c:619
Inline: False
```
```
In drivers/spi/spi.c (ffffffff81752700)
Location: drivers/spi/spi.c:57
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff8178a010)
Location: drivers/usb/core/sysfs.c:1009
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817e0830)
Location: drivers/input/serio/serio.c:362
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8186a990)
Location: drivers/mmc/core/sdio_bus.c:50
Inline: False
```
**Symbols:**

```
ffffffff81538960-ffffffff815389a6: modalias_show (STB_LOCAL)
ffffffff81565240-ffffffff81565274: modalias_show (STB_LOCAL)
ffffffff816041c0-ffffffff816041ee: modalias_show (STB_LOCAL)
ffffffff81617c80-ffffffff81617cad: modalias_show (STB_LOCAL)
ffffffff81661310-ffffffff8166132a: modalias_show (STB_LOCAL)
ffffffff816a5640-ffffffff816a569a: modalias_show (STB_LOCAL)
ffffffff816f3ac0-ffffffff816f3ae8: modalias_show (STB_LOCAL)
ffffffff81752700-ffffffff8175274f: modalias_show (STB_LOCAL)
ffffffff8178a010-ffffffff8178a07b: modalias_show (STB_LOCAL)
ffffffff817e0830-ffffffff817e0870: modalias_show (STB_LOCAL)
ffffffff8186a990-ffffffff8186a9c8: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81568350)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815955d0)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81636be0)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164b940)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff81696d50)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (ffffffff816de5d0)
Location: drivers/base/platform.c:884
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff8172cdd0)
Location: drivers/nvdimm/bus.c:650
Inline: False
```
```
In drivers/dax/bus.c (ffffffff8173fc60)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffffffff8178e200)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff817c8470)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81821100)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818ae8b0)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff81568350-ffffffff81568396: modalias_show (STB_LOCAL)
ffffffff815955d0-ffffffff81595604: modalias_show (STB_LOCAL)
ffffffff81636be0-ffffffff81636c0e: modalias_show (STB_LOCAL)
ffffffff8164b940-ffffffff8164b96a: modalias_show (STB_LOCAL)
ffffffff81696d50-ffffffff81696d6a: modalias_show (STB_LOCAL)
ffffffff816de5d0-ffffffff816de62b: modalias_show (STB_LOCAL)
ffffffff8172cdd0-ffffffff8172cdfa: modalias_show (STB_LOCAL)
ffffffff8173fc60-ffffffff8173fc81: modalias_show (STB_LOCAL)
ffffffff8178e200-ffffffff8178e24f: modalias_show (STB_LOCAL)
ffffffff817c8470-ffffffff817c84e0: modalias_show (STB_LOCAL)
ffffffff81821100-ffffffff81821140: modalias_show (STB_LOCAL)
ffffffff818ae8b0-ffffffff818ae8e8: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81589630)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815b6850)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81658940)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166ddd0)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff816b98e0)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (ffffffff81702850)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81751660)
Location: drivers/nvdimm/bus.c:648
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81763e40)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffffffff817b1e10)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff817f8fb0)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81852570)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818e0d10)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff81589630-ffffffff81589676: modalias_show (STB_LOCAL)
ffffffff815b6850-ffffffff815b6884: modalias_show (STB_LOCAL)
ffffffff81658940-ffffffff8165896e: modalias_show (STB_LOCAL)
ffffffff8166ddd0-ffffffff8166ddfa: modalias_show (STB_LOCAL)
ffffffff816b98e0-ffffffff816b98fa: modalias_show (STB_LOCAL)
ffffffff81702850-ffffffff817028ab: modalias_show (STB_LOCAL)
ffffffff81751660-ffffffff8175168a: modalias_show (STB_LOCAL)
ffffffff81763e40-ffffffff81763e61: modalias_show (STB_LOCAL)
ffffffff817b1e10-ffffffff817b1e5f: modalias_show (STB_LOCAL)
ffffffff817f8fb0-ffffffff817f9020: modalias_show (STB_LOCAL)
ffffffff81852570-ffffffff818525b0: modalias_show (STB_LOCAL)
ffffffff818e0d10-ffffffff818e0d48: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81630520)
Location: drivers/pci/pci-sysfs.c:249
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8165fff0)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81709150)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171df80)
Location: drivers/xen/xenbus/xenbus_probe.c:398
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff8176dc70)
Location: drivers/tty/serdev/core.c:26
Inline: False
```
```
In drivers/base/platform.c (ffffffff817bc390)
Location: drivers/base/platform.c:1012
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff8180ff30)
Location: drivers/nvdimm/bus.c:653
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81823c90)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffffffff81877ba0)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff818c9130)
Location: drivers/usb/core/sysfs.c:1135
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81924420)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819409b0)
Location: drivers/i2c/i2c-core-base.c:477
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b3e10)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff81630520-ffffffff81630566: modalias_show (STB_LOCAL)
ffffffff8165fff0-ffffffff81660024: modalias_show (STB_LOCAL)
ffffffff81709150-ffffffff8170917e: modalias_show (STB_LOCAL)
ffffffff8171df80-ffffffff8171dfaa: modalias_show (STB_LOCAL)
ffffffff8176dc70-ffffffff8176dc8a: modalias_show (STB_LOCAL)
ffffffff817bc390-ffffffff817bc3eb: modalias_show (STB_LOCAL)
ffffffff8180ff30-ffffffff8180ff5c: modalias_show (STB_LOCAL)
ffffffff81823c90-ffffffff81823cb1: modalias_show (STB_LOCAL)
ffffffff81877ba0-ffffffff81877bef: modalias_show (STB_LOCAL)
ffffffff818c9130-ffffffff818c91a0: modalias_show (STB_LOCAL)
ffffffff81924420-ffffffff81924460: modalias_show (STB_LOCAL)
ffffffff819409b0-ffffffff819409fc: modalias_show (STB_LOCAL)
ffffffff819b3e10-ffffffff819b3e48: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81655b90)
Location: drivers/pci/pci-sysfs.c:258
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816812b0)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81726100)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173aef0)
Location: drivers/xen/xenbus/xenbus_probe.c:399
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff81788650)
Location: drivers/tty/serdev/core.c:26
Inline: False
```
```
In drivers/base/platform.c (ffffffff817d0fd0)
Location: drivers/base/platform.c:1267
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff8181ee70)
Location: drivers/nvdimm/bus.c:650
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81832a80)
Location: drivers/dax/bus.c:1195
Inline: False
```
```
In drivers/spi/spi.c (ffffffff818864b0)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff818d4280)
Location: drivers/usb/core/sysfs.c:1135
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff8192c1d0)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81946d80)
Location: drivers/i2c/i2c-core-base.c:605
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff819b62f0)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff81655b90-ffffffff81655be5: modalias_show (STB_LOCAL)
ffffffff816812b0-ffffffff816812e4: modalias_show (STB_LOCAL)
ffffffff81726100-ffffffff8172612e: modalias_show (STB_LOCAL)
ffffffff8173aef0-ffffffff8173af1a: modalias_show (STB_LOCAL)
ffffffff81788650-ffffffff8178866a: modalias_show (STB_LOCAL)
ffffffff817d0fd0-ffffffff817d1015: modalias_show (STB_LOCAL)
ffffffff8181ee70-ffffffff8181ee9c: modalias_show (STB_LOCAL)
ffffffff81832a80-ffffffff81832aa1: modalias_show (STB_LOCAL)
ffffffff818864b0-ffffffff818864ff: modalias_show (STB_LOCAL)
ffffffff818d4280-ffffffff818d42f0: modalias_show (STB_LOCAL)
ffffffff8192c1d0-ffffffff8192c210: modalias_show (STB_LOCAL)
ffffffff81946d80-ffffffff81946dcc: modalias_show (STB_LOCAL)
ffffffff819b62f0-ffffffff819b6328: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81638850)
Location: drivers/pci/pci-sysfs.c:258
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81664100)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff816853f0)
Location: drivers/acpi/device_sysfs.c:329
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81709d10)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e9d0)
Location: drivers/xen/xenbus/xenbus_probe.c:465
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff8176bfa0)
Location: drivers/tty/serdev/core.c:26
Inline: False
```
```
In drivers/base/platform.c (ffffffff817b49f0)
Location: drivers/base/platform.c:1266
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81802190)
Location: drivers/nvdimm/bus.c:645
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81815cc0)
Location: drivers/dax/bus.c:1196
Inline: False
```
```
In drivers/spi/spi.c (ffffffff81868d20)
Location: drivers/spi/spi.c:56
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff818b7850)
Location: drivers/usb/core/sysfs.c:1138
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff8190f6d0)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff8192a680)
Location: drivers/i2c/i2c-core-base.c:649
Inline: True
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff8199aaa0)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff81638850-ffffffff816388a6: modalias_show (STB_LOCAL)
ffffffff81664100-ffffffff81664134: modalias_show (STB_LOCAL)
ffffffff816853f0-ffffffff81685437: modalias_show (STB_LOCAL)
ffffffff81709d10-ffffffff81709d3e: modalias_show (STB_LOCAL)
ffffffff8171e9d0-ffffffff8171e9fa: modalias_show (STB_LOCAL)
ffffffff8176bfa0-ffffffff8176bfba: modalias_show (STB_LOCAL)
ffffffff817b49f0-ffffffff817b4a35: modalias_show (STB_LOCAL)
ffffffff81802190-ffffffff818021bc: modalias_show (STB_LOCAL)
ffffffff81815cc0-ffffffff81815ce1: modalias_show (STB_LOCAL)
ffffffff81868d20-ffffffff81868d6f: modalias_show (STB_LOCAL)
ffffffff818b7850-ffffffff818b78c0: modalias_show (STB_LOCAL)
ffffffff8190f6d0-ffffffff8190f710: modalias_show (STB_LOCAL)
ffffffff8192a680-ffffffff8192a6cc: modalias_show (STB_LOCAL)
ffffffff8199aaa0-ffffffff8199aad8: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff816a8b80)
Location: drivers/pci/pci-sysfs.c:258
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff816d6fe0)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff816fa6b0)
Location: drivers/acpi/device_sysfs.c:334
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81785770)
Location: drivers/virtio/virtio.c:37
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179d780)
Location: drivers/xen/xenbus/xenbus_probe.c:462
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff817f16e0)
Location: drivers/tty/serdev/core.c:26
Inline: False
```
```
In drivers/base/platform.c (ffffffff8183de30)
Location: drivers/base/platform.c:1230
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff8188c650)
Location: drivers/nvdimm/bus.c:639
Inline: False
```
```
In drivers/dax/bus.c (ffffffff818a0300)
Location: drivers/dax/bus.c:1194
Inline: False
```
```
In drivers/spi/spi.c (ffffffff818f8820)
Location: drivers/spi/spi.c:56
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff8194d2e0)
Location: drivers/usb/core/sysfs.c:1114
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff819b04d0)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff819cd820)
Location: drivers/i2c/i2c-core-base.c:650
Inline: True
```
```
In drivers/eisa/eisa-bus.c (ffffffff81a1e790)
Location: drivers/eisa/eisa-bus.c:174
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81a473e0)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff816a8b80-ffffffff816a8bd6: modalias_show (STB_LOCAL)
ffffffff816d6fe0-ffffffff816d7014: modalias_show (STB_LOCAL)
ffffffff816fa6b0-ffffffff816fa6f7: modalias_show (STB_LOCAL)
ffffffff81785770-ffffffff8178579e: modalias_show (STB_LOCAL)
ffffffff8179d780-ffffffff8179d7aa: modalias_show (STB_LOCAL)
ffffffff817f16e0-ffffffff817f16fa: modalias_show (STB_LOCAL)
ffffffff8183de30-ffffffff8183de75: modalias_show (STB_LOCAL)
ffffffff8188c650-ffffffff8188c67c: modalias_show (STB_LOCAL)
ffffffff818a0300-ffffffff818a0321: modalias_show (STB_LOCAL)
ffffffff818f8820-ffffffff818f886f: modalias_show (STB_LOCAL)
ffffffff8194d2e0-ffffffff8194d350: modalias_show (STB_LOCAL)
ffffffff819b04d0-ffffffff819b0510: modalias_show (STB_LOCAL)
ffffffff819cd820-ffffffff819cd86c: modalias_show (STB_LOCAL)
ffffffff81a1e790-ffffffff81a1e7b6: modalias_show (STB_LOCAL)
ffffffff81a473e0-ffffffff81a47418: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff817cb8a0)
Location: drivers/pci/pci-sysfs.c:279
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81800980)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff81827af0)
Location: drivers/acpi/device_sysfs.c:335
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff818bc4f0)
Location: drivers/virtio/virtio.c:38
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d6ec0)
Location: drivers/xen/xenbus/xenbus_probe.c:463
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff81931d40)
Location: drivers/tty/serdev/core.c:26
Inline: False
```
```
In drivers/base/platform.c (ffffffff81980c00)
Location: drivers/base/platform.c:1239
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff819d5ad0)
Location: drivers/nvdimm/bus.c:627
Inline: False
```
```
In drivers/dax/bus.c (ffffffff819e98f0)
Location: drivers/dax/bus.c:1224
Inline: False
```
```
In drivers/spi/spi.c (ffffffff81a4a600)
Location: drivers/spi/spi.c:56
Inline: True
```
```
In drivers/usb/core/sysfs.c (ffffffff81aa6060)
Location: drivers/usb/core/sysfs.c:1114
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81b0f220)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81b2fa20)
Location: drivers/i2c/i2c-core-base.c:651
Inline: True
```
```
In drivers/eisa/eisa-bus.c (ffffffff81b86f60)
Location: drivers/eisa/eisa-bus.c:174
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81bb5280)
Location: drivers/mmc/core/sdio_bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff817cb8a0-ffffffff817cb90d: modalias_show (STB_LOCAL)
ffffffff81800980-ffffffff818009c6: modalias_show (STB_LOCAL)
ffffffff81827af0-ffffffff81827b5b: modalias_show (STB_LOCAL)
ffffffff818bc4f0-ffffffff818bc52a: modalias_show (STB_LOCAL)
ffffffff818d6ec0-ffffffff818d6ef6: modalias_show (STB_LOCAL)
ffffffff81931d40-ffffffff81931d64: modalias_show (STB_LOCAL)
ffffffff81980c00-ffffffff81980c5a: modalias_show (STB_LOCAL)
ffffffff819d5ad0-ffffffff819d5b05: modalias_show (STB_LOCAL)
ffffffff819e98f0-ffffffff819e991b: modalias_show (STB_LOCAL)
ffffffff81a4a600-ffffffff81a4a667: modalias_show (STB_LOCAL)
ffffffff81aa6060-ffffffff81aa60e3: modalias_show (STB_LOCAL)
ffffffff81b0f220-ffffffff81b0f272: modalias_show (STB_LOCAL)
ffffffff81b2fa20-ffffffff81b2fa84: modalias_show (STB_LOCAL)
ffffffff81b86f60-ffffffff81b86f90: modalias_show (STB_LOCAL)
ffffffff81bb5280-ffffffff81bb52c4: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff818e90e0)
Location: drivers/pci/pci-sysfs.c:280
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff8192df00)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff81959af0)
Location: drivers/acpi/device_sysfs.c:335
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81a0b130)
Location: drivers/virtio/virtio.c:38
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a29500)
Location: drivers/xen/xenbus/xenbus_probe.c:463
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff81a90730)
Location: drivers/tty/serdev/core.c:26
Inline: False
```
```
In drivers/base/platform.c (ffffffff81aee760)
Location: drivers/base/platform.c:1239
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81b50660)
Location: drivers/nvdimm/bus.c:640
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81b66290)
Location: drivers/dax/bus.c:1224
Inline: False
```
```
In drivers/spi/spi.c (ffffffff81bd13a0)
Location: drivers/spi/spi.c:58
Inline: True
```
```
In drivers/usb/core/sysfs.c (ffffffff81c2cd30)
Location: drivers/usb/core/sysfs.c:1110
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81c9f5e0)
Location: drivers/input/serio/serio.c:347
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81cc3f60)
Location: drivers/i2c/i2c-core-base.c:652
Inline: True
```
```
In drivers/eisa/eisa-bus.c (ffffffff81d26410)
Location: drivers/eisa/eisa-bus.c:174
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81d599b0)
Location: drivers/mmc/core/sdio_bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff818e90e0-ffffffff818e914d: modalias_show (STB_LOCAL)
ffffffff8192df00-ffffffff8192df46: modalias_show (STB_LOCAL)
ffffffff81959af0-ffffffff81959b5b: modalias_show (STB_LOCAL)
ffffffff81a0b130-ffffffff81a0b167: modalias_show (STB_LOCAL)
ffffffff81a29500-ffffffff81a29536: modalias_show (STB_LOCAL)
ffffffff81a90730-ffffffff81a90754: modalias_show (STB_LOCAL)
ffffffff81aee760-ffffffff81aee7ba: modalias_show (STB_LOCAL)
ffffffff81b50660-ffffffff81b50695: modalias_show (STB_LOCAL)
ffffffff81b66290-ffffffff81b662bb: modalias_show (STB_LOCAL)
ffffffff81bd13a0-ffffffff81bd1407: modalias_show (STB_LOCAL)
ffffffff81c2cd30-ffffffff81c2cdb0: modalias_show (STB_LOCAL)
ffffffff81c9f5e0-ffffffff81c9f632: modalias_show (STB_LOCAL)
ffffffff81cc3f60-ffffffff81cc3fc4: modalias_show (STB_LOCAL)
ffffffff81d26410-ffffffff81d26440: modalias_show (STB_LOCAL)
ffffffff81d599b0-ffffffff81d599f4: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8192c6f0)
Location: drivers/pci/pci-sysfs.c:280
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81972190)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff8199ff50)
Location: drivers/acpi/device_sysfs.c:335
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81a53fc0)
Location: drivers/virtio/virtio.c:38
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a72c00)
Location: drivers/xen/xenbus/xenbus_probe.c:463
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff81adbf40)
Location: drivers/tty/serdev/core.c:26
Inline: False
```
```
In drivers/base/platform.c (ffffffff81b3cb20)
Location: drivers/base/platform.c:1243
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81ba3b30)
Location: drivers/nvdimm/bus.c:640
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81bb98a0)
Location: drivers/dax/bus.c:1254
Inline: False
```
```
In drivers/spi/spi.c (ffffffff81c29010)
Location: drivers/spi/spi.c:58
Inline: True
```
```
In drivers/usb/core/sysfs.c (ffffffff81c93e90)
Location: drivers/usb/core/sysfs.c:1110
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81d06920)
Location: drivers/input/serio/serio.c:347
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81d2b920)
Location: drivers/i2c/i2c-core-base.c:667
Inline: True
```
```
In drivers/eisa/eisa-bus.c (ffffffff81d8f640)
Location: drivers/eisa/eisa-bus.c:174
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81dc4350)
Location: drivers/mmc/core/sdio_bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff8192c6f0-ffffffff8192c75d: modalias_show (STB_LOCAL)
ffffffff81972190-ffffffff819721d6: modalias_show (STB_LOCAL)
ffffffff8199ff50-ffffffff8199ffbb: modalias_show (STB_LOCAL)
ffffffff81a53fc0-ffffffff81a53ff7: modalias_show (STB_LOCAL)
ffffffff81a72c00-ffffffff81a72c36: modalias_show (STB_LOCAL)
ffffffff81adbf40-ffffffff81adbf64: modalias_show (STB_LOCAL)
ffffffff81b3cb20-ffffffff81b3cb7a: modalias_show (STB_LOCAL)
ffffffff81ba3b30-ffffffff81ba3b65: modalias_show (STB_LOCAL)
ffffffff81bb98a0-ffffffff81bb98cb: modalias_show (STB_LOCAL)
ffffffff81c29010-ffffffff81c29077: modalias_show (STB_LOCAL)
ffffffff81c93e90-ffffffff81c93f10: modalias_show (STB_LOCAL)
ffffffff81d06920-ffffffff81d06972: modalias_show (STB_LOCAL)
ffffffff81d2b920-ffffffff81d2b984: modalias_show (STB_LOCAL)
ffffffff81d8f640-ffffffff81d8f670: modalias_show (STB_LOCAL)
ffffffff81dc4350-ffffffff81dc4394: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81974f80)
Location: drivers/pci/pci-sysfs.c:279
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff819bc200)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/acpi/device_sysfs.c (ffffffff819e85c0)
Location: drivers/acpi/device_sysfs.c:333
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81aa4c40)
Location: drivers/virtio/virtio.c:38
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81ac4d60)
Location: drivers/xen/xenbus/xenbus_probe.c:463
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f220)
Location: drivers/tty/serdev/core.c:28
Inline: False
```
```
In drivers/base/platform.c (ffffffff81b94650)
Location: drivers/base/platform.c:1243
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81bf7d20)
Location: drivers/nvdimm/bus.c:640
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81c0df00)
Location: drivers/dax/bus.c:1255
Inline: False
```
```
In drivers/spi/spi.c (ffffffff81cdba50)
Location: drivers/spi/spi.c:58
Inline: True
```
```
In drivers/usb/core/sysfs.c (ffffffff81d48950)
Location: drivers/usb/core/sysfs.c:1107
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81dbc550)
Location: drivers/input/serio/serio.c:347
Inline: False
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de17e0)
Location: drivers/i2c/i2c-core-base.c:670
Inline: True
```
```
In drivers/eisa/eisa-bus.c (ffffffff81e46f50)
Location: drivers/eisa/eisa-bus.c:174
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7cc30)
Location: drivers/mmc/core/sdio_bus.c:47
Inline: False
```
**Symbols:**

```
ffffffff81974f80-ffffffff81974fe4: modalias_show (STB_LOCAL)
ffffffff819bc200-ffffffff819bc246: modalias_show (STB_LOCAL)
ffffffff819e85c0-ffffffff819e862b: modalias_show (STB_LOCAL)
ffffffff81aa4c40-ffffffff81aa4c77: modalias_show (STB_LOCAL)
ffffffff81ac4d60-ffffffff81ac4d96: modalias_show (STB_LOCAL)
ffffffff81b2f220-ffffffff81b2f244: modalias_show (STB_LOCAL)
ffffffff81b94650-ffffffff81b946aa: modalias_show (STB_LOCAL)
ffffffff81bf7d20-ffffffff81bf7d55: modalias_show (STB_LOCAL)
ffffffff81c0df00-ffffffff81c0df2b: modalias_show (STB_LOCAL)
ffffffff81cdba50-ffffffff81cdbab7: modalias_show (STB_LOCAL)
ffffffff81d48950-ffffffff81d489d0: modalias_show (STB_LOCAL)
ffffffff81dbc550-ffffffff81dbc5a2: modalias_show (STB_LOCAL)
ffffffff81de17e0-ffffffff81de1844: modalias_show (STB_LOCAL)
ffffffff81e46f50-ffffffff81e46f80: modalias_show (STB_LOCAL)
ffffffff81e7cc30-ffffffff81e7cc74: modalias_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/bus/fsl-mc/fsl-mc-bus.c (ffff800010680450)
Location: drivers/bus/fsl-mc/fsl-mc-bus.c:140
Inline: False
```
```
In drivers/pci/pci-sysfs.c (ffff8000106ede20)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffff80001073ef88)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffff800010820d20)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffff800010838948)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/tty/serdev/core.c (ffff8000108a9d20)
Location: drivers/tty/serdev/core.c:25
Inline: True
```
```
In drivers/base/platform.c (ffff8000108ee1d0)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/nvdimm/bus.c (ffff800010951650)
Location: drivers/nvdimm/bus.c:648
Inline: False
```
```
In drivers/dax/bus.c (ffff800010963f70)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffff8000109c2230)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffff800010a2a0d0)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (ffff800010a91fc0)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffff800010b3aea8)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffff800010680450-ffff800010680494: modalias_show (STB_LOCAL)
ffff8000106ede20-ffff8000106ede88: modalias_show (STB_LOCAL)
ffff80001073ef88-ffff80001073efd4: modalias_show (STB_LOCAL)
ffff800010820d20-ffff800010820d64: modalias_show (STB_LOCAL)
ffff800010838948-ffff800010838990: modalias_show (STB_LOCAL)
ffff8000108a9d20-ffff8000108a9d80: modalias_show (STB_LOCAL)
ffff8000108ee1d0-ffff8000108ee260: modalias_show (STB_LOCAL)
ffff800010951650-ffff800010951698: modalias_show (STB_LOCAL)
ffff800010963f70-ffff800010963fac: modalias_show (STB_LOCAL)
ffff8000109c2230-ffff8000109c22a0: modalias_show (STB_LOCAL)
ffff800010a2a0d0-ffff800010a2a154: modalias_show (STB_LOCAL)
ffff800010a91fc0-ffff800010a9200c: modalias_show (STB_LOCAL)
ffff800010b3aea8-ffff800010b3aef0: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (c0888f30)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (c08c3b80)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (c093ebc4)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/tty/serdev/core.c (c09a5eb8)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (c09dbf2c)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/dax/bus.c (c0a3ab34)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (c0aaee8c)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (c0affd78)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (c0b75e74)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (c0c15980)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
c0888f30-c0888f9c: modalias_show (STB_LOCAL)
c08c3b80-c08c3bcc: modalias_show (STB_LOCAL)
c093ebc4-c093ebfc: modalias_show (STB_LOCAL)
c09a5eb8-c09a5edc: modalias_show (STB_LOCAL)
c09dbf2c-c09dbf84: modalias_show (STB_LOCAL)
c0a3ab34-c0a3ab64: modalias_show (STB_LOCAL)
c0aaee8c-c0aaeec4: modalias_show (STB_LOCAL)
c0affd78-c0affe0c: modalias_show (STB_LOCAL)
c0b75e74-c0b75ec0: modalias_show (STB_LOCAL)
c0c15980-c0c159d0: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/platforms/pseries/vio.c (c0000000000ffea0)
Location: arch/powerpc/platforms/pseries/vio.c:1542
Inline: False
```
```
In drivers/pci/pci-sysfs.c (c00000000086a490)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (c000000000898a20)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (c0000000008ca7d0)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/tty/serdev/core.c (c000000000940d70)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (c000000000986d80)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/nvdimm/bus.c (c0000000009fdfe0)
Location: drivers/nvdimm/bus.c:648
Inline: False
```
```
In drivers/dax/bus.c (c000000000a1a770)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (c000000000a85580)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (c000000000ae6820)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (c000000000b6e650)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (c000000000c37b30)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
c0000000000ffea0-c0000000000fff7c: modalias_show (STB_LOCAL)
c00000000086a490-c00000000086a4fc: modalias_show (STB_LOCAL)
c000000000898a20-c000000000898a78: modalias_show (STB_LOCAL)
c0000000008ca7d0-c0000000008ca820: modalias_show (STB_LOCAL)
c000000000940d70-c000000000940dac: modalias_show (STB_LOCAL)
c000000000986d80-c000000000986e24: modalias_show (STB_LOCAL)
c0000000009fdfe0-c0000000009fe034: modalias_show (STB_LOCAL)
c000000000a1a770-c000000000a1a7b8: modalias_show (STB_LOCAL)
c000000000a85580-c000000000a855d0: modalias_show (STB_LOCAL)
c000000000ae6820-c000000000ae68a8: modalias_show (STB_LOCAL)
c000000000b6e650-c000000000b6e6a8: modalias_show (STB_LOCAL)
c000000000c37b30-c000000000c37b84: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffe0004c2932)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffe0004ee56a)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffe000517d96)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffe00055ed82)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (ffffffe000581314)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffe0005c18c4)
Location: drivers/nvdimm/bus.c:648
Inline: False
```
```
In drivers/dax/bus.c (ffffffe0005d1002)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffffffe000615b30)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffe00064b9e6)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffe0006a4d72)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffe00071288a)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffe0004c2932-ffffffe0004c2998: modalias_show (STB_LOCAL)
ffffffe00055ed82-ffffffe00055edb6: modalias_show (STB_LOCAL)
ffffffe000581314-ffffffe000581386: modalias_show (STB_LOCAL)
ffffffe0005c18c4-ffffffe0005c1908: modalias_show (STB_LOCAL)
ffffffe0005d1002-ffffffe0005d1038: modalias_show (STB_LOCAL)
ffffffe000615b30-ffffffe000615b74: modalias_show (STB_LOCAL)
ffffffe0006a4d72-ffffffe0006a4dbc: modalias_show (STB_LOCAL)
ffffffe0004ee56a-ffffffe0004ee5b4: modalias_show (STB_LOCAL)
ffffffe000517d96-ffffffe000517dd8: modalias_show (STB_LOCAL)
ffffffe00064b9e6-ffffffe00064ba58: modalias_show (STB_LOCAL)
ffffffe00071288a-ffffffe0007128d0: modalias_show (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157d4c0)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815aaac0)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff8161e7e0)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81633be0)
Location: drivers/xen/xenbus/xenbus_probe.c:398
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff8167f340)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (ffffffff816c7fa0)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81705d50)
Location: drivers/nvdimm/bus.c:648
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81718530)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffffffff817768f0)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff817b1390)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81807650)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818846d0)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff8157d4c0-ffffffff8157d506: modalias_show (STB_LOCAL)
ffffffff815aaac0-ffffffff815aaaf4: modalias_show (STB_LOCAL)
ffffffff8161e7e0-ffffffff8161e80e: modalias_show (STB_LOCAL)
ffffffff81633be0-ffffffff81633c0a: modalias_show (STB_LOCAL)
ffffffff8167f340-ffffffff8167f35a: modalias_show (STB_LOCAL)
ffffffff816c7fa0-ffffffff816c7ffb: modalias_show (STB_LOCAL)
ffffffff81705d50-ffffffff81705d7a: modalias_show (STB_LOCAL)
ffffffff81718530-ffffffff81718551: modalias_show (STB_LOCAL)
ffffffff817768f0-ffffffff8177693f: modalias_show (STB_LOCAL)
ffffffff817b1390-ffffffff817b1400: modalias_show (STB_LOCAL)
ffffffff81807650-ffffffff81807690: modalias_show (STB_LOCAL)
ffffffff818846d0-ffffffff81884708: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8156c290)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff81599c60)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81612ed0)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/base/platform.c (ffffffff816a32a0)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff816d97d0)
Location: drivers/nvdimm/bus.c:648
Inline: False
```
```
In drivers/dax/bus.c (ffffffff816f0a60)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffffffff817566a0)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff817a2dc0)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff817ced60)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/hv/vmbus_drv.c (ffffffff8184d3f0)
Location: drivers/hv/vmbus_drv.c:192
Inline: False
```
**Symbols:**

```
ffffffff8156c290-ffffffff8156c2d6: modalias_show (STB_LOCAL)
ffffffff81599c60-ffffffff81599c94: modalias_show (STB_LOCAL)
ffffffff81612ed0-ffffffff81612efe: modalias_show (STB_LOCAL)
ffffffff816a32a0-ffffffff816a32fb: modalias_show (STB_LOCAL)
ffffffff816d97d0-ffffffff816d97fa: modalias_show (STB_LOCAL)
ffffffff816f0a60-ffffffff816f0a81: modalias_show (STB_LOCAL)
ffffffff817566a0-ffffffff817566ef: modalias_show (STB_LOCAL)
ffffffff817a2dc0-ffffffff817a2e30: modalias_show (STB_LOCAL)
ffffffff817ced60-ffffffff817ceda0: modalias_show (STB_LOCAL)
ffffffff8184d3f0-ffffffff8184d484: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff8157d380)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815ab050)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff8164c780)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81661c10)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff816ad720)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (ffffffff816f6510)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff81744b20)
Location: drivers/nvdimm/bus.c:648
Inline: False
```
```
In drivers/dax/bus.c (ffffffff81757300)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffffffff817a6c90)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff817ede30)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81846700)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818d5b70)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff8157d380-ffffffff8157d3c6: modalias_show (STB_LOCAL)
ffffffff815ab050-ffffffff815ab084: modalias_show (STB_LOCAL)
ffffffff8164c780-ffffffff8164c7ae: modalias_show (STB_LOCAL)
ffffffff81661c10-ffffffff81661c3a: modalias_show (STB_LOCAL)
ffffffff816ad720-ffffffff816ad73a: modalias_show (STB_LOCAL)
ffffffff816f6510-ffffffff816f656b: modalias_show (STB_LOCAL)
ffffffff81744b20-ffffffff81744b4a: modalias_show (STB_LOCAL)
ffffffff81757300-ffffffff81757321: modalias_show (STB_LOCAL)
ffffffff817a6c90-ffffffff817a6cdf: modalias_show (STB_LOCAL)
ffffffff817ede30-ffffffff817edea0: modalias_show (STB_LOCAL)
ffffffff81846700-ffffffff81846740: modalias_show (STB_LOCAL)
ffffffff818d5b70-ffffffff818d5ba8: modalias_show (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
ssize_t modalias_show(struct device *dev, struct device_attribute *attr, char *buf);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-sysfs.c (ffffffff81597830)
Location: drivers/pci/pci-sysfs.c:266
Inline: False
```
```
In drivers/rapidio/rio-sysfs.c (ffffffff815c49e0)
Location: drivers/rapidio/rio-sysfs.c:87
Inline: False
```
```
In drivers/virtio/virtio.c (ffffffff81666e20)
Location: drivers/virtio/virtio.c:36
Inline: False
```
```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167c1e0)
Location: drivers/xen/xenbus/xenbus_probe.c:397
Inline: False
```
```
In drivers/tty/serdev/core.c (ffffffff816c7b80)
Location: drivers/tty/serdev/core.c:25
Inline: False
```
```
In drivers/base/platform.c (ffffffff81710db0)
Location: drivers/base/platform.c:949
Inline: True
```
```
In drivers/nvdimm/bus.c (ffffffff8175ff60)
Location: drivers/nvdimm/bus.c:648
Inline: False
```
```
In drivers/dax/bus.c (ffffffff817727a0)
Location: drivers/dax/bus.c:314
Inline: False
```
```
In drivers/spi/spi.c (ffffffff817c0b10)
Location: drivers/spi/spi.c:60
Inline: False
```
```
In drivers/usb/core/sysfs.c (ffffffff81808070)
Location: drivers/usb/core/sysfs.c:1130
Inline: False
```
```
In drivers/input/serio/serio.c (ffffffff81861d10)
Location: drivers/input/serio/serio.c:350
Inline: False
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff818f2690)
Location: drivers/mmc/core/sdio_bus.c:46
Inline: False
```
**Symbols:**

```
ffffffff81597830-ffffffff81597876: modalias_show (STB_LOCAL)
ffffffff815c49e0-ffffffff815c4a14: modalias_show (STB_LOCAL)
ffffffff81666e20-ffffffff81666e4e: modalias_show (STB_LOCAL)
ffffffff8167c1e0-ffffffff8167c20a: modalias_show (STB_LOCAL)
ffffffff816c7b80-ffffffff816c7b9a: modalias_show (STB_LOCAL)
ffffffff81710db0-ffffffff81710e0b: modalias_show (STB_LOCAL)
ffffffff8175ff60-ffffffff8175ff8a: modalias_show (STB_LOCAL)
ffffffff817727a0-ffffffff817727c1: modalias_show (STB_LOCAL)
ffffffff817c0b10-ffffffff817c0b5f: modalias_show (STB_LOCAL)
ffffffff81808070-ffffffff818080e0: modalias_show (STB_LOCAL)
ffffffff81861d10-ffffffff81861d50: modalias_show (STB_LOCAL)
ffffffff818f2690-ffffffff818f26c8: modalias_show (STB_LOCAL)
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
