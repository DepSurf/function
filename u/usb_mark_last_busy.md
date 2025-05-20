# Function: <code>usb_mark_last_busy</code>

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
In drivers/usb/core/hub.c (ffffffff81608937)
Location: include/linux/usb.h:683
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_new_device
  - drivers/usb/core/hub.c:usb_port_suspend
```
```
In drivers/usb/core/driver.c (ffffffff81613869)
Location: include/linux/usb.h:683
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_runtime_suspend
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
In drivers/usb/core/hub.c (ffffffff816688fc)
Location: include/linux/usb.h:680
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81675627)
Location: include/linux/usb.h:680
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff8169661c)
Location: include/linux/usb.h:680
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816a32b7)
Location: include/linux/usb.h:680
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff816aba4b)
Location: include/linux/usb.h:751
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff816b845f)
Location: include/linux/usb.h:751
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff81716eab)
Location: include/linux/usb.h:752
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81723d6f)
Location: include/linux/usb.h:752
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff81755cf8)
Location: include/linux/usb.h:772
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817629f0)
Location: include/linux/usb.h:772
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff8177a2ba)
Location: include/linux/usb.h:772
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81786ff4)
Location: include/linux/usb.h:772
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff817b7df2)
Location: include/linux/usb.h:772
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817c5477)
Location: include/linux/usb.h:772
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff817e85c2)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817f5e17)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff818b7ae4)
Location: include/linux/usb.h:772
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818c5d07)
Location: include/linux/usb.h:772
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
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
In drivers/usb/core/hub.c (ffffffff818c63f4)
Location: include/linux/usb.h:774
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818d1bd7)
Location: include/linux/usb.h:774
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
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
In drivers/usb/core/hub.c (ffffffff818a9758)
Location: include/linux/usb.h:776
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff818b51e7)
Location: include/linux/usb.h:776
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
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
In drivers/usb/core/hub.c (ffffffff8193e668)
Location: include/linux/usb.h:769
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8194a767)
Location: include/linux/usb.h:769
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
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
In drivers/usb/core/hub.c (ffffffff81a96693)
Location: include/linux/usb.h:769
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81aa343e)
Location: include/linux/usb.h:769
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
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
In drivers/usb/core/hub.c (ffffffff81c19208)
Location: include/linux/usb.h:798
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c28fbe)
Location: include/linux/usb.h:798
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
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
In drivers/usb/core/hub.c (ffffffff81c801c1)
Location: include/linux/usb.h:814
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81c8ff8e)
Location: include/linux/usb.h:814
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
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
In drivers/usb/core/hub.c (ffffffff81d34b91)
Location: include/linux/usb.h:806
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81d44b3e)
Location: include/linux/usb.h:806
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_unbind_device
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
In drivers/usb/core/hub.c (ffff800010a17bac)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffff800010a26e28)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (c0aefc10)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c0afced0)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_autosuspend_device
  - drivers/usb/core/driver.c:usb_resume_both
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
In drivers/usb/core/hub.c (c000000000ad0a10)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (c000000000ae28a0)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffe00063c95e)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffe000648c76)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff817a09a2)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817ae1f7)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff817927e2)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff8179fbf7)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff817dd442)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff817eac97)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
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
In drivers/usb/core/hub.c (ffffffff817f7712)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:usb_port_suspend
  - drivers/usb/core/hub.c:usb_new_device
```
```
In drivers/usb/core/driver.c (ffffffff81804ed7)
Location: include/linux/usb.h:771
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_runtime_suspend
  - drivers/usb/core/driver.c:usb_autopm_get_interface_no_resume
  - drivers/usb/core/driver.c:usb_autopm_put_interface_no_suspend
  - drivers/usb/core/driver.c:usb_autopm_put_interface_async
  - drivers/usb/core/driver.c:usb_autopm_put_interface
  - drivers/usb/core/driver.c:usb_resume_both
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_probe_interface
  - drivers/usb/core/driver.c:usb_probe_interface
```
</details>
</li>
</ul>

## Differences
