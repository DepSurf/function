# Function: <code>pm_request_idle</code>

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
In drivers/base/dd.c (ffffffff8154b446)
Location: include/linux/pm_runtime.h:206
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81557632)
Location: include/linux/pm_runtime.h:206
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff8159d736)
Location: include/linux/pm_runtime.h:212
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff815a96ca)
Location: include/linux/pm_runtime.h:212
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff815cbab6)
Location: include/linux/pm_runtime.h:215
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff815d839a)
Location: include/linux/pm_runtime.h:215
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff815e069d)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff815ec9f5)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff8164776d)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81653db7)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff81682c5d)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8168ebf6)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff816a289d)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff816aef26)
Location: include/linux/pm_runtime.h:203
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff816db657)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff816e999c)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff816ff627)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8170d9fc)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff817b990e)
Location: include/linux/pm_runtime.h:214
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff817c961c)
Location: include/linux/pm_runtime.h:214
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff817ce93e)
Location: include/linux/pm_runtime.h:335
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff817de11c)
Location: include/linux/pm_runtime.h:335
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
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
In drivers/base/dd.c (ffffffff817b233e)
Location: include/linux/pm_runtime.h:335
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff817c245f)
Location: include/linux/pm_runtime.h:335
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
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
In drivers/base/dd.c (ffffffff8183b72a)
Location: include/linux/pm_runtime.h:342
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8184c121)
Location: include/linux/pm_runtime.h:342
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:pm_runtime_release_supplier
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
In drivers/base/core.c (ffffffff819767d1)
Location: include/linux/pm_runtime.h:371
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/dd.c (ffffffff8197dccb)
Location: include/linux/pm_runtime.h:371
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81992653)
Location: include/linux/pm_runtime.h:371
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
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
In drivers/base/core.c (ffffffff81ae2a11)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/dd.c (ffffffff81aeb54b)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81b02af3)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
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
In drivers/base/core.c (ffffffff81b30931)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/dd.c (ffffffff81b3981a)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81b50ba3)
Location: include/linux/pm_runtime.h:375
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
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
In drivers/base/core.c (ffffffff81b87f31)
Location: include/linux/pm_runtime.h:373
Inline: True
Inline callers:
  - drivers/base/core.c:device_link_release_fn
```
```
In drivers/base/dd.c (ffffffff81b912da)
Location: include/linux/pm_runtime.h:373
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:__driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff81ba9123)
Location: include/linux/pm_runtime.h:373
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:pm_runtime_drop_link
  - drivers/base/power/runtime.c:__pm_runtime_set_status
  - drivers/base/power/runtime.c:rpm_suspend
  - drivers/base/power/runtime.c:__rpm_put_suppliers
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
In drivers/base/dd.c (ffff8000108ea750)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffff8000108fcf28)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (c09d8800)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (c09e8674)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (c000000000981970)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (c000000000999840)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffe00057e570)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffe00058be90)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff816c4e17)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff816d314c)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff816a0097)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff816ae430)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff816f32e7)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff817016bc)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
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
In drivers/base/dd.c (ffffffff8170db17)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/dd.c:__device_attach
  - drivers/base/dd.c:__device_attach_async_helper
  - drivers/base/dd.c:driver_probe_device
```
```
In drivers/base/power/runtime.c (ffffffff8171c46a)
Location: include/linux/pm_runtime.h:204
Inline: True
Inline callers:
  - drivers/base/power/runtime.c:__pm_runtime_set_status
```
</details>
</li>
</ul>

## Differences
