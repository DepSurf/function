# Function: <code>kobject_get_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eb520)
Location: lib/kobject.c:146
Inline: False
Direct callers:
  - lib/kobject.c:kobject_rename
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
```
**Symbols:**

```
ffffffff813eb520-ffffffff813eb5fd: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431870)
Location: lib/kobject.c:146
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/base/power/domain.c:pm_genpd_summary_show
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
```
**Symbols:**

```
ffffffff81431870-ffffffff81431955: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144dae0)
Location: lib/kobject.c:146
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - drivers/base/power/domain.c:pm_genpd_summary_show
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
```
**Symbols:**

```
ffffffff8144dae0-ffffffff8144dbc5: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818edda0)
Location: lib/kobject.c:146
Inline: False
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_summary_show
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff818edda0-ffffffff818ede89: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81973fc0)
Location: lib/kobject.c:146
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_devices_show
  - drivers/base/power/domain.c:genpd_summary_show
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81973fc0-ffffffff819740a9: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0510)
Location: lib/kobject.c:163
Inline: False
Direct callers:
  - drivers/base/power/domain.c:genpd_devices_show
  - drivers/base/power/domain.c:genpd_summary_show
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff819d0510-ffffffff819d05f9: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a09a70)
Location: lib/kobject.c:163
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a09a70-ffffffff81a09b59: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79980)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a79980-ffffffff81a79a69: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0ce0)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81ab0ce0-ffffffff81ab0dc9: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815ea8c0)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
```
**Symbols:**

```
ffffffff815ea8c0-ffffffff815ea949: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f1e0)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/usb/core/hub.c:port_over_current_notify
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
```
**Symbols:**

```
ffffffff8160f1e0-ffffffff8160f269: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f28c0)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
```
**Symbols:**

```
ffffffff815f28c0-ffffffff815f29a9: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8165faa0)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
```
**Symbols:**

```
ffffffff8165faa0-ffffffff8165fb86: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff817795f0)
Location: lib/kobject.c:139
Inline: False
Direct callers:
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
```
**Symbols:**

```
ffffffff817795f0-ffffffff8177968d: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *kobject_get_path(const struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820225f0)
Location: lib/kobject.c:143
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff820225f0-ffffffff82022681: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *kobject_get_path(const struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2650)
Location: lib/kobject.c:145
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:genpd_summary_one
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff820a2650-ffffffff820a26e1: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *kobject_get_path(const struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217a6d0)
Location: lib/kobject.c:152
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:devices_show
  - drivers/pmdomain/core.c:genpd_summary_one
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff8217a6d0-ffffffff8217a761: kobject_get_path (STB_GLOBAL)
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
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8a6d8)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffff800010d8a6d8-ffff800010d8a7f4: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e853bc)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c0e853bc-c0e854b8: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecc1b0)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
c000000000ecc1b0-c000000000ecc364: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b3d22)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffe0008b3d22-ffffffe0008b3e04: kobject_get_path (STB_GLOBAL)
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
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4fb30)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a4fb30-ffffffff81a4fc19: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0cc30)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81a0cc30-ffffffff81a0cd19: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abbf20)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81abbf20-ffffffff81abc009: kobject_get_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
char *kobject_get_path(struct kobject *kobj, gfp_t gfp_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac83a0)
Location: lib/kobject.c:171
Inline: False
Direct callers:
  - drivers/base/power/domain.c:devices_show
  - drivers/base/power/domain.c:summary_show
  - drivers/usb/core/hub.c:port_event
  - drivers/input/input.c:input_register_device
  - drivers/input/input.c:input_devices_seq_show
  - lib/kobject.c:kobject_move
  - lib/kobject.c:kobject_rename
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
  - lib/kobject_uevent.c:kobject_synth_uevent
```
**Symbols:**

```
ffffffff81ac83a0-ffffffff81ac8489: kobject_get_path (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobject *kobj</code> ➡️ <code>const struct kobject *kobj</code>
</li>
</ul>
</details>
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
