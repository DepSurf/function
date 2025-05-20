# Function: <code>to_xenbus_device</code>

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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff814ceb74)
Location: include/xen/xenbus.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (0)
Location: include/xen/xenbus.h:80
Inline: True
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: include/xen/xenbus.h:80
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8151f64b)
Location: include/xen/xenbus.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff815206f4)
Location: include/xen/xenbus.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81521cc3)
Location: include/xen/xenbus.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8154bafb)
Location: include/xen/xenbus.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8154cb74)
Location: include/xen/xenbus.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8154e193)
Location: include/xen/xenbus.h:80
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8155fe0b)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff81560f04)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8156261f)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815c40ab)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff815c51e8)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815c691f)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff815fcba5)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff815fd872)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815ff0a5)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81617c55)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff81618942)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8161a175)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8164b905)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8164c632)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8164df25)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8166dd95)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8166eac2)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81670405)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171df45)
Location: include/xen/xenbus.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8171f297)
Location: include/xen/xenbus.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81720a05)
Location: include/xen/xenbus.h:84
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8173aeb5)
Location: include/xen/xenbus.h:93
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8173c1f7)
Location: include/xen/xenbus.h:93
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8173d965)
Location: include/xen/xenbus.h:93
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8171e995)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:set_spurious_threshold
  - drivers/xen/xenbus/xenbus_probe.c:show_spurious_threshold
  - drivers/xen/xenbus/xenbus_probe.c:show_jiffies_eoi_delayed
  - drivers/xen/xenbus/xenbus_probe.c:show_spurious_events
  - drivers/xen/xenbus/xenbus_probe.c:show_events
  - drivers/xen/xenbus/xenbus_probe.c:show_event_channels
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8171fd57)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff817214e5)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8179d745)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_store
  - drivers/xen/xenbus/xenbus_probe.c:spurious_threshold_show
  - drivers/xen/xenbus/xenbus_probe.c:jiffies_eoi_delayed_show
  - drivers/xen/xenbus/xenbus_probe.c:spurious_events_show
  - drivers/xen/xenbus/xenbus_probe.c:events_show
  - drivers/xen/xenbus/xenbus_probe.c:event_channels_show
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8179eb77)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff817a0305)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_resume
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff818d7110)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff818d8538)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff818da245)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:non_essential_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:essential_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81a297b0)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff81a2aea8)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_reclaim_memory
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2ceb5)
Location: include/xen/xenbus.h:99
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:non_essential_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:essential_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/xen/xenbus/xenbus_probe.c (ffff80001083891c)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffff800010839764)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffff80001083b43c)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81633ba5)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff81634b82)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff816364c5)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe.c (ffffffff81661bd5)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff81662902)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81664245)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
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
In drivers/xen/xenbus/xenbus_probe.c (ffffffff8167c1a5)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe.c:state_show
  - drivers/xen/xenbus/xenbus_probe.c:modalias_show
  - drivers/xen/xenbus/xenbus_probe.c:devtype_show
  - drivers/xen/xenbus/xenbus_probe.c:nodename_show
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_release
  - drivers/xen/xenbus/xenbus_probe.c:cleanup_dev
  - drivers/xen/xenbus/xenbus_probe.c:cmp_dev
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
```
In drivers/xen/xenbus/xenbus_probe_backend.c (ffffffff8167ced2)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_uevent_backend
```
```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8167e805)
Location: include/xen/xenbus.h:81
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:is_device_connecting
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_probe
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_uevent_frontend
```
</details>
</li>
</ul>

## Differences
