# Function: <code>pci_set_drvdata</code>

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
In arch/x86/events/intel/uncore.c (ffffffff8101616d)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/gpio/gpio-intel-mid.c (ffffffff81429e9b)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81476552)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8147750d)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff814c28a3)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150c8b3)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8151fe32)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81520fc5)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81523516)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/usb/dwc2/pci.c (ffffffff8162f8a0)
Location: include/linux/pci.h:1546
Inline: True
Inline callers:
  - drivers/usb/dwc2/pci.c:dwc2_pci_remove
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
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
In arch/x86/events/intel/uncore.c (ffffffff81015826)
Location: include/linux/pci.h:1604
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814c4a92)
Location: include/linux/pci.h:1604
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814c5a52)
Location: include/linux/pci.h:1604
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81512e13)
Location: include/linux/pci.h:1604
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155eb4e)
Location: include/linux/pci.h:1604
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81572c8a)
Location: include/linux/pci.h:1604
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81573e20)
Location: include/linux/pci.h:1604
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81576456)
Location: include/linux/pci.h:1604
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff810159e6)
Location: include/linux/pci.h:1666
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814e6a82)
Location: include/linux/pci.h:1666
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814e7aba)
Location: include/linux/pci.h:1666
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8153ef43)
Location: include/linux/pci.h:1666
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8158b0ad)
Location: include/linux/pci.h:1666
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8159f302)
Location: include/linux/pci.h:1666
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff815a0490)
Location: include/linux/pci.h:1666
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff815a2ae6)
Location: include/linux/pci.h:1666
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff81013ec7)
Location: include/linux/pci.h:1698
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff814f26e3)
Location: include/linux/pci.h:1698
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff814f36c2)
Location: include/linux/pci.h:1698
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81552cc3)
Location: include/linux/pci.h:1698
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8159f32d)
Location: include/linux/pci.h:1698
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
```
```
In drivers/char/agp/amd64-agp.c (ffffffff815b3190)
Location: include/linux/pci.h:1698
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff815b3538)
Location: include/linux/pci.h:1698
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff815b664c)
Location: include/linux/pci.h:1698
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff8101435a)
Location: include/linux/pci.h:1754
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81532da3)
Location: include/linux/pci.h:1754
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81533d82)
Location: include/linux/pci.h:1754
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815b6633)
Location: include/linux/pci.h:1754
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8160482d)
Location: include/linux/pci.h:1754
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81619dd0)
Location: include/linux/pci.h:1754
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8161a188)
Location: include/linux/pci.h:1754
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff8161d35c)
Location: include/linux/pci.h:1754
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff81014ea9)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81512936)
Location: include/linux/pci.h:1757
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8153bedd)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815687f4)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81569aeb)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff815eeaa3)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8163da92)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81653a45)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81653e3c)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff8165700e)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/i2c/busses/i2c-amd-pci-mp2.c (ffffffff817dcc16)
Location: include/linux/pci.h:1757
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_remove
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-pci-mp2.c:amd_mp2_pci_probe
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
In arch/x86/events/intel/uncore.c (ffffffff81015949)
Location: include/linux/pci.h:1791
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81528166)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815533a8)
Location: include/linux/pci.h:1791
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff81580253)
Location: include/linux/pci.h:1791
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8158154b)
Location: include/linux/pci.h:1791
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff816091a3)
Location: include/linux/pci.h:1791
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165bd02)
Location: include/linux/pci.h:1791
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81671c45)
Location: include/linux/pci.h:1791
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8167203c)
Location: include/linux/pci.h:1791
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff8167510e)
Location: include/linux/pci.h:1791
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff81016c4c)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81557400)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81583248)
Location: include/linux/pci.h:1865
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815b08bf)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815b1beb)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8163d014)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8169125d)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816a77da)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816a7adc)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816aac42)
Location: include/linux/pci.h:1865
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff810175fc)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81578a30)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815a4c28)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815d183f)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815d2b6b)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8165f4f4)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816b3d4d)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816ca51a)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816ca81c)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816cd982)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff8101918c)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8161da30)
Location: include/linux/pci.h:1869
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8164da87)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8167b3d0)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8167c2d6)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170e5c4)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81766c7d)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8177f3b7)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8177f4ac)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81782850)
Location: include/linux/pci.h:1869
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff8101995e)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81644270)
Location: include/linux/pci.h:1877
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81671c47)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8169b440)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff8169c2b6)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8172b394)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81781bbd)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81c09a88)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff817973cc)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81c0a260)
Location: include/linux/pci.h:1877
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff8101ac20)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81626fd0)
Location: include/linux/pci.h:1893
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81654157)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8167e2c2)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81bf103d)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8170f124)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8176541d)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81bfb4fd)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8177a0ac)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81bfbce7)
Location: include/linux/pci.h:1893
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff8101d610)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff816968a0)
Location: include/linux/pci.h:1954
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff816c5f87)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff816f3262)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81ced76d)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8178ba54)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff817e9b5d)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81cfc177)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81800130)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81cfc971)
Location: include/linux/pci.h:1954
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff8101fbd4)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff817b77a0)
Location: include/linux/pci.h:1973
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff817ebe62)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8181fa53)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff81eb4e1e)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff818c3605)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8192953d)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81ec49a6)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8193f517)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81ec51ac)
Location: include/linux/pci.h:1973
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff81024424)
Location: include/linux/pci.h:2012
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff818d1f24)
Location: include/linux/pci.h:2012
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81912552)
Location: include/linux/pci.h:2012
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff8194f02f)
Location: include/linux/pci.h:2012
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819501db)
Location: include/linux/pci.h:2012
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a13c55)
Location: include/linux/pci.h:2012
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81a85f2d)
Location: include/linux/pci.h:2012
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81a881b9)
Location: include/linux/pci.h:2012
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aa0b7b)
Location: include/linux/pci.h:2012
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81aa0fe6)
Location: include/linux/pci.h:2012
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81aa4a35)
Location: include/linux/pci.h:2012
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff81024148)
Location: include/linux/pci.h:2104
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81914f24)
Location: include/linux/pci.h:2104
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81955be2)
Location: include/linux/pci.h:2104
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff819953f1)
Location: include/linux/pci.h:2104
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819966cb)
Location: include/linux/pci.h:2104
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5ccb5)
Location: include/linux/pci.h:2104
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81ad167d)
Location: include/linux/pci.h:2104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81ad38a9)
Location: include/linux/pci.h:2104
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81aec45a)
Location: include/linux/pci.h:2104
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81aec8c6)
Location: include/linux/pci.h:2104
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81af0355)
Location: include/linux/pci.h:2104
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In arch/x86/events/intel/uncore.c (ffffffff8102a278)
Location: include/linux/pci.h:2170
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8195ce94)
Location: include/linux/pci.h:2170
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8199f104)
Location: include/linux/pci.h:2170
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff819dfa4d)
Location: include/linux/pci.h:2170
Inline: True
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff819e0d43)
Location: include/linux/pci.h:2170
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaeac4)
Location: include/linux/pci.h:2170
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81b22f85)
Location: include/linux/pci.h:2170
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff81b254dd)
Location: include/linux/pci.h:2170
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff81b3f99a)
Location: include/linux/pci.h:2170
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff81b3fe06)
Location: include/linux/pci.h:2170
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81b43895)
Location: include/linux/pci.h:2170
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
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
In drivers/pci/hotplug/shpchp_core.c (ffff80001070d9a0)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (ffff80001075b0f4)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffff80001075da1c)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffff8000108280a0)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffff80001088f8cc)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
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
In drivers/video/fbdev/imsttfb.c (c08ddf50)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (c08e0388)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (c09460f8)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (c098cab8)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/mfd/sm501.c (c0a0de8c)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/mfd/sm501.c:sm501_pci_probe
```
```
In drivers/usb/dwc2/pci.c (c0b21c4c)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/usb/dwc2/pci.c:dwc2_pci_probe
  - drivers/usb/dwc2/pci.c:dwc2_pci_remove
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
In drivers/video/fbdev/imsttfb.c (c0000000008c1110)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (c0000000008c24f8)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/video/fbdev/gxt4500.c (c0000000008c3b74)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/gxt4500.c:gxt4500_probe
```
```
In drivers/virtio/virtio_pci_common.c (c0000000008d47f0)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (c000000000937e2c)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
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
In drivers/pci/hotplug/shpchp_core.c (ffffffe0004da06c)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (ffffffe000506c0e)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffe0005078ba)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffe00051e8ce)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffe000559518)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
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
In arch/x86/events/intel/uncore.c (ffffffff810175fc)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598438)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815c584f)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c6b7b)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81625364)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816797ad)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8168ff6a)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8169026c)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816933d2)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/nvme/host/pci.c (ffffffff817501ee)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_probe
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
In arch/x86/events/intel/uncore.c (ffffffff81016a2c)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815875c8)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff816199e4)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8165889d)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff8166d95a)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff8166dc5c)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff81670dc2)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/nvme/host/pci.c (ffffffff8173008e)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_probe
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
In arch/x86/events/intel/uncore.c (ffffffff810175bc)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff8156c780)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff81598978)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815c5ddf)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815c710b)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81653334)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816a7b8d)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816be1da)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816be4dc)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816c1642)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
```
In drivers/i2c/busses/i2c-amd-mp2-pci.c (ffffffff81868252)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
  - drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe
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
In arch/x86/events/intel/uncore.c (ffffffff810177fc)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:uncore_pci_remove
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
  - arch/x86/events/intel/uncore.c:uncore_pci_probe
```
```
In drivers/pwm/pwm-lpss-pci.c (ffffffff81586c80)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff815b2db8)
Location: include/linux/pci.h:1859
Inline: True
```
```
In drivers/video/fbdev/imsttfb.c (ffffffff815df97f)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/imsttfb.c:imsttfb_probe
```
```
In drivers/video/fbdev/asiliantfb.c (ffffffff815e0cab)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/video/fbdev/asiliantfb.c:asiliantfb_pci_init
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff8166d9c4)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff816c1fed)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:serial8250_io_resume
  - drivers/tty/serial/8250/8250_pci.c:pciserial_init_one
```
```
In drivers/char/agp/amd64-agp.c (ffffffff816d87aa)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/amd64-agp.c:agp_amd64_probe
```
```
In drivers/char/agp/intel-agp.c (ffffffff816d8aac)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/intel-agp.c:agp_intel_probe
```
```
In drivers/char/agp/via-agp.c (ffffffff816dbc12)
Location: include/linux/pci.h:1859
Inline: True
Inline callers:
  - drivers/char/agp/via-agp.c:agp_via_probe
```
</details>
</li>
</ul>

## Differences
