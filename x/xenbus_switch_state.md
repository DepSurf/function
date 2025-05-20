# Function: <code>xenbus_switch_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cba30)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkif_recover
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff814cba30-ffffffff814cba4f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151c682)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8151c610-ffffffff8151c62f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81548b52)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff81548ae0-ffffffff81548aff: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155c90e)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff8155c8a0-ffffffff8155c8bf: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c0c0e)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff815c0ba0-ffffffff815c0bbf: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f8ec2)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff815f8e50-ffffffff815f8e6f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81613f72)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81613f00-ffffffff81613f1f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81647cb3)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81647c40-ffffffff81647c5f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166a153)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8166a0e0-ffffffff8166a0ff: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171a343)
Location: drivers/xen/xenbus/xenbus_client.c:263
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_closing
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff8171a080-ffffffff8171a09f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737483)
Location: drivers/xen/xenbus/xenbus_client.c:266
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_closing
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_xdp
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff817371c0-ffffffff817371df: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171aec3)
Location: drivers/xen/xenbus/xenbus_client.c:266
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_xdp
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff8171abf0-ffffffff8171ac0f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81799893)
Location: drivers/xen/xenbus/xenbus_client.c:266
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81799470-ffffffff8179948f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d275a)
Location: drivers/xen/xenbus/xenbus_client.c:266
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff818d25d0-ffffffff818d25ec: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a2474a)
Location: drivers/xen/xenbus/xenbus_client.c:266
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81a24590-ffffffff81a245ac: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6dc8a)
Location: drivers/xen/xenbus/xenbus_client.c:266
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81a6dad0-ffffffff81a6daec: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81abfd2a)
Location: drivers/xen/xenbus/xenbus_client.c:275
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_frontend_dev_shutdown
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81abfb70-ffffffff81abfb8c: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff800010834af4)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffff800010834a30-ffff800010834a78: xenbus_switch_state (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8162ffc3)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_freeze
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_restore
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8162ff50-ffffffff8162ff6f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165df93)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8165df20-ffffffff8165df3f: xenbus_switch_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xenbus_switch_state(struct xenbus_device *dev, enum xenbus_state state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816788f3)
Location: drivers/xen/xenbus/xenbus_client.c:247
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_dev_fatal
  - drivers/xen/xenbus/xenbus_client.c:xenbus_frontend_closed
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_shutdown
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_backend_changed
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81678880-ffffffff8167889f: xenbus_switch_state (STB_GLOBAL)
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
