# Function: <code>pm_runtime_set_suspended</code>

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
In drivers/base/power/runtime.c (ffffffff81557d87)
Location: include/linux/pm_runtime.h:262
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/usb/core/hub.c (ffffffff81608853)
Location: include/linux/pm_runtime.h:262
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81614dc2)
Location: include/linux/pm_runtime.h:262
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff816c4c8d)
Location: include/linux/pm_runtime.h:262
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff816c6aa8)
Location: include/linux/pm_runtime.h:262
Inline: True
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
In drivers/base/power/runtime.c (ffffffff815a982f)
Location: include/linux/pm_runtime.h:268
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
```
```
In drivers/usb/core/hub.c (ffffffff81668520)
Location: include/linux/pm_runtime.h:268
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81674db6)
Location: include/linux/pm_runtime.h:268
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff81727c4d)
Location: include/linux/pm_runtime.h:268
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81729a78)
Location: include/linux/pm_runtime.h:268
Inline: True
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
In drivers/base/power/runtime.c (ffffffff815d8623)
Location: include/linux/pm_runtime.h:271
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/scsi/hosts.c (ffffffff8162f5cd)
Location: include/linux/pm_runtime.h:271
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81696240)
Location: include/linux/pm_runtime.h:271
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816a2a46)
Location: include/linux/pm_runtime.h:271
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff8175acbd)
Location: include/linux/pm_runtime.h:271
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff8175cb78)
Location: include/linux/pm_runtime.h:271
Inline: True
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
In drivers/base/power/runtime.c (ffffffff815ecbd4)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/scsi/hosts.c (ffffffff81644698)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff816ab63a)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816b7b66)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff8177706d)
Location: include/linux/pm_runtime.h:259
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff8177b398)
Location: include/linux/pm_runtime.h:259
Inline: True
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
In drivers/base/power/runtime.c (ffffffff81653f86)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff81656166)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff816ad62b)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81716a9a)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8172342b)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff817ed47d)
Location: include/linux/pm_runtime.h:259
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff817f1dd8)
Location: include/linux/pm_runtime.h:259
Inline: True
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
In drivers/base/power/runtime.c (ffffffff8168ee18)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff816917f3)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff816e9f6b)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81755997)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81760e30)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff8183658c)
Location: include/linux/pm_runtime.h:259
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff8183b087)
Location: include/linux/pm_runtime.h:259
Inline: True
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
In drivers/base/power/runtime.c (ffffffff816af146)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff816b1de3)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff8170d9db)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81779ebd)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817853f0)
Location: include/linux/pm_runtime.h:259
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff8186257c)
Location: include/linux/pm_runtime.h:259
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81867017)
Location: include/linux/pm_runtime.h:259
Inline: True
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
In drivers/base/power/runtime.c (ffffffff816e9ad1)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff816ebbec)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81749231)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817b7b13)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817c3980)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff818a66cd)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff818aae68)
Location: include/linux/pm_runtime.h:260
Inline: True
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
In drivers/base/power/runtime.c (ffffffff8170db31)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff8170fc7e)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff8176d381)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817e82e3)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817f4300)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff818d8b2d)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff818dd2b8)
Location: include/linux/pm_runtime.h:260
Inline: True
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
In drivers/base/power/runtime.c (ffffffff817c9895)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff817cbe5a)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff8182f94b)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff818b7802)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818c3e60)
Location: include/linux/pm_runtime.h:270
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff819ab7fd)
Location: include/linux/pm_runtime.h:270
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff819b03a8)
Location: include/linux/pm_runtime.h:270
Inline: True
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
In drivers/base/power/runtime.c (ffffffff817de395)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff817e08ca)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81c1645d)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff818c6112)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818cfd50)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff819ae3ad)
Location: include/linux/pm_runtime.h:509
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff819b2918)
Location: include/linux/pm_runtime.h:509
Inline: True
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
In drivers/base/power/runtime.c (ffffffff817c2775)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff817c44ca)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81c08167)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff818a944e)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818b3380)
Location: include/linux/pm_runtime.h:509
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff819929dd)
Location: include/linux/pm_runtime.h:509
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff819970f8)
Location: include/linux/pm_runtime.h:509
Inline: True
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
In drivers/base/power/runtime.c (ffffffff8184c335)
Location: include/linux/pm_runtime.h:519
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff8184e8aa)
Location: include/linux/pm_runtime.h:519
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81d0bfeb)
Location: include/linux/pm_runtime.h:519
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff8193e35b)
Location: include/linux/pm_runtime.h:519
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff819487d0)
Location: include/linux/pm_runtime.h:519
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff81a3e4dd)
Location: include/linux/pm_runtime.h:519
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81a434c8)
Location: include/linux/pm_runtime.h:519
Inline: True
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
In drivers/base/power/runtime.c (ffffffff81991cff)
Location: include/linux/pm_runtime.h:548
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff81994796)
Location: include/linux/pm_runtime.h:548
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81ed4f23)
Location: include/linux/pm_runtime.h:548
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81a9636a)
Location: include/linux/pm_runtime.h:548
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81aa12da)
Location: include/linux/pm_runtime.h:548
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff81bab804)
Location: include/linux/pm_runtime.h:548
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81bb0eef)
Location: include/linux/pm_runtime.h:548
Inline: True
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
In drivers/base/power/runtime.c (ffffffff81b0217d)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff81b05256)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81b76ef7)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81c18d74)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c2695a)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff81d4ebe4)
Location: include/linux/pm_runtime.h:552
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81d54d6f)
Location: include/linux/pm_runtime.h:552
Inline: True
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
In drivers/base/power/runtime.c (ffffffff81b5026d)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff81b52c46)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81bcab87)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81c7fd4b)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c8d920)
Location: include/linux/pm_runtime.h:552
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff81db94f4)
Location: include/linux/pm_runtime.h:552
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81dbf6ef)
Location: include/linux/pm_runtime.h:552
Inline: True
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
In drivers/base/power/runtime.c (ffffffff81ba87ed)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
  - drivers/base/power/runtime.c:pm_runtime_force_suspend
  - drivers/base/power/runtime.c:pm_runtime_remove
```
```
In drivers/base/power/main.c (ffffffff81bab920)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81c1f7b7)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81d3476c)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81d42450)
Location: include/linux/pm_runtime.h:550
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff81e71af4)
Location: include/linux/pm_runtime.h:550
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81e77dff)
Location: include/linux/pm_runtime.h:550
Inline: True
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
In drivers/amba/bus.c (ffff8000107b9584)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/base/power/runtime.c (ffff8000108fd15c)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffff8000109002ec)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffff80001096fa34)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffff800010a17674)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffff800010a24da4)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffff800010b33204)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (ffff800010b37578)
Location: include/linux/pm_runtime.h:260
Inline: True
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
In drivers/amba/bus.c (c08e5f04)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/amba/bus.c:amba_remove
  - drivers/amba/bus.c:amba_probe
```
```
In drivers/clk/samsung/clk-exynos5-subcmu.c (c1585328)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/clk/samsung/clk-exynos5-subcmu.c:exynos5_subcmu_probe
```
```
In drivers/base/power/runtime.c (c09e8804)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (c09ea554)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (c0a44cac)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (c0aef734)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c0afb3e0)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/i2c/busses/i2c-imx.c (c0b9be50)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-imx.c:i2c_imx_probe
```
```
In drivers/mmc/core/mmc.c (c0c0dc4c)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (c0c11ee8)
Location: include/linux/pm_runtime.h:260
Inline: True
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
In drivers/base/power/runtime.c (c000000000999a00)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (c00000000099da08)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (c000000000a290f0)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (c000000000ad037c)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c000000000adfc14)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (c000000000c2d6d4)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (c000000000c32d04)
Location: include/linux/pm_runtime.h:260
Inline: True
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
In drivers/base/power/runtime.c (ffffffe00058bfb0)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/scsi/hosts.c (ffffffe0005d9a0e)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffe00063c4e2)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffe0006470b0)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffe00070b91c)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffe00070f4f0)
Location: include/linux/pm_runtime.h:260
Inline: True
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
In drivers/base/power/runtime.c (ffffffff816d3281)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff816d5c3e)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81721a71)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817a06c3)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817ac6e0)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff8187c4ed)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff81880c78)
Location: include/linux/pm_runtime.h:260
Inline: True
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
In drivers/base/power/runtime.c (ffffffff816ae571)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff816b066e)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff816faea1)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff81792490)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8179e0e0)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/base/power/runtime.c (ffffffff817017f1)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff8170393e)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff81760841)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817dd163)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817e9180)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff818cd98d)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff818d2118)
Location: include/linux/pm_runtime.h:260
Inline: True
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
In drivers/base/power/runtime.c (ffffffff8171c5b1)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_force_resume
```
```
In drivers/base/power/main.c (ffffffff8171e68e)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/base/power/main.c:device_resume_noirq
```
```
In drivers/scsi/hosts.c (ffffffff8177bea1)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:scsi_add_host_with_dma
```
```
In drivers/usb/core/hub.c (ffffffff817f7433)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818036b0)
Location: include/linux/pm_runtime.h:260
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_driver_claim_interface
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
```
In drivers/mmc/core/mmc.c (ffffffff818ea4ad)
Location: include/linux/pm_runtime.h:260
Inline: True
```
```
In drivers/mmc/core/sd.c (ffffffff818eec38)
Location: include/linux/pm_runtime.h:260
Inline: True
```
</details>
</li>
</ul>

## Differences
