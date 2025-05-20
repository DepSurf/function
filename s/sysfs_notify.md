# Function: <code>sysfs_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8128c4e0)
Location: fs/sysfs/file.c:167
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8128c4e0-ffffffff8128c567: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812b9b30)
Location: fs/sysfs/file.c:173
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff812b9b30-ffffffff812b9bb7: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812cf270)
Location: fs/sysfs/file.c:173
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff812cf270-ffffffff812cf2f7: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff812dc9c0)
Location: fs/sysfs/file.c:175
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff812dc9c0-ffffffff812dca47: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813012c0)
Location: fs/sysfs/file.c:175
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff813012c0-ffffffff81301347: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8132ef90)
Location: fs/sysfs/file.c:173
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8132ef90-ffffffff8132f015: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81346350)
Location: fs/sysfs/file.c:173
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81346350-ffffffff813463d5: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136e660)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8136e660-ffffffff8136e6e3: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81386810)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff81386810-ffffffff81386893: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813d1470)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/hwmon/hwmon.c:hwmon_notify_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff813d1470-ffffffff813d14f3: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e3070)
Location: fs/sysfs/file.c:173
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/hwmon/hwmon.c:hwmon_notify_event
```
**Symbols:**

```
ffffffff813e3070-ffffffff813e30f3: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813e9cb0)
Location: fs/sysfs/file.c:183
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/hwmon/hwmon.c:hwmon_notify_event
```
**Symbols:**

```
ffffffff813e9cb0-ffffffff813e9d33: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8143ba30)
Location: fs/sysfs/file.c:183
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_notify_error_sysfs
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/hwmon/hwmon.c:hwmon_notify_event
```
**Symbols:**

```
ffffffff8143ba30-ffffffff8143bab3: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff814b6e30)
Location: fs/sysfs/file.c:180
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_notify_error_sysfs
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/hwmon/hwmon.c:hwmon_notify_event
```
**Symbols:**

```
ffffffff814b6e30-ffffffff814b6ec3: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8154e190)
Location: fs/sysfs/file.c:180
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_notify_error_sysfs
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/hwmon/hwmon.c:hwmon_notify_event
```
**Symbols:**

```
ffffffff8154e190-ffffffff8154e223: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff81585e50)
Location: fs/sysfs/file.c:180
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_notify_error_sysfs
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/sysfs.c:usb_update_wireless_status_attr
  - drivers/hwmon/hwmon.c:hwmon_notify_event
```
**Symbols:**

```
ffffffff81585e50-ffffffff81585ee3: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff815be930)
Location: fs/sysfs/file.c:192
Inline: False
Direct callers:
  - fs/ext4/sysfs.c:ext4_notify_error_sysfs
  - drivers/video/backlight/backlight.c:backlight_device_set_brightness
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/core/sysfs.c:usb_update_wireless_status_attr
  - drivers/hwmon/hwmon.c:hwmon_notify_event
```
**Symbols:**

```
ffffffff815be930-ffffffff815be9c3: sysfs_notify (STB_GLOBAL)
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
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffff800010456388)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffff800010456388-ffff800010456448: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c0618438)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/usb/musb/musb_core.c:musb_irq_work
  - drivers/usb/gadget/udc/core.c:usb_gadget_state_work
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
c0618438-c06184ec: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (c000000000570120)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
c000000000570120-c0000000005701fc: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffe0002e7c28)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffe0002e7c28-ffffffe0002e7cb0: sysfs_notify (STB_GLOBAL)
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
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137edf0)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8137edf0-ffffffff8137ee73: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8136f880)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8136f880-ffffffff8136f903: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff8137c8c0)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff8137c8c0-ffffffff8137c943: sysfs_notify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sysfs_notify(struct kobject *kobj, const char *dir, const char *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/sysfs/file.c (ffffffff813903a0)
Location: fs/sysfs/file.c:172
Inline: False
Direct callers:
  - drivers/video/backlight/backlight.c:backlight_generate_event
  - drivers/tty/tty_io.c:console_sysfs_notify
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/usb/core/hub.c:port_event
  - drivers/md/md.c:read_rdev
  - drivers/md/md.c:rdev_set_badblocks
  - drivers/md/md.c:md_reap_sync_thread
  - drivers/md/md.c:remove_and_add_spares
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:action_store
  - drivers/md/md.c:level_store
```
**Symbols:**

```
ffffffff813903a0-ffffffff81390423: sysfs_notify (STB_GLOBAL)
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
