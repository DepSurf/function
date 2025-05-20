# Function: <code>memdup_array_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec.c (ffffffff8122da72)
Location: include/linux/string.h:29
Inline: True
Inline callers:
  - kernel/kexec.c:__ia32_sys_kexec_load
  - kernel/kexec.c:__x64_sys_kexec_load
```
```
In kernel/watch_queue.c (ffffffff813b32c1)
Location: include/linux/string.h:29
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_set_filter
```
```
In drivers/tty/vt/keyboard.c (ffffffff81affaf1)
Location: include/linux/string.h:29
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
```
```
In drivers/gpu/drm/drm_lease.c (ffffffff81c9fa0f)
Location: include/linux/string.h:29
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_lease.c:drm_mode_create_lease_ioctl
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d17bfc)
Location: include/linux/string.h:29
Inline: True
```
```
In drivers/i2c/i2c-dev.c (ffffffff81dea1c9)
Location: include/linux/string.h:29
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_ioctl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
