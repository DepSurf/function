# Function: <code>xenbus_scanf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd9f0)
Location: drivers/xen/xenbus/xenbus_xs.c:545
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff814cd9f0-ffffffff814cda89: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e560)
Location: drivers/xen/xenbus/xenbus_xs.c:540
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff8151e560-ffffffff8151e5ff: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a9e0)
Location: drivers/xen/xenbus/xenbus_xs.c:540
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8154a9e0-ffffffff8154aa7f: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155ef00)
Location: drivers/xen/xenbus/xenbus_xs.c:557
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8155ef00-ffffffff8155efaa: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3230)
Location: drivers/xen/xenbus/xenbus_xs.c:560
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff815c3230-ffffffff815c32da: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fb8d0)
Location: drivers/xen/xenbus/xenbus_xs.c:562
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff815fb8d0-ffffffff815fb973: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616980)
Location: drivers/xen/xenbus/xenbus_xs.c:562
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff81616980-ffffffff81616a23: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164a640)
Location: drivers/xen/xenbus/xenbus_xs.c:565
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8164a640-ffffffff8164a6e7: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166cad0)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8166cad0-ffffffff8166cb77: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d070)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8171d070-ffffffff8171d190: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8173a030)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8173a030-ffffffff8173a150: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d960)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8171d960-ffffffff8171da80: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179c710)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8179c710-ffffffff8179c830: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d5c80)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff818d5c80-ffffffff818d5d7e: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a280f0)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff81a280f0-ffffffff81a281ee: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a717f0)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff81a717f0-ffffffff81a718ee: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac3950)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff81ac3950-ffffffff81ac3a4e: xenbus_scanf (STB_GLOBAL)
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
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff8000108371c8)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffff8000108371c8-ffff8000108372b0: xenbus_scanf (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81632940)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff81632940-ffffffff816329e7: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81660910)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff81660910-ffffffff816609b7: xenbus_scanf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenbus_scanf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167aef0)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/cpu_hotplug.c:vcpu_online
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_backend_state_changed
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/xen/xen-balloon.c:watch_target
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
```
**Symbols:**

```
ffffffff8167aef0-ffffffff8167af97: xenbus_scanf (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
