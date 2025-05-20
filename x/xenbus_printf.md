# Function: <code>xenbus_printf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cda90)
Location: drivers/xen/xenbus/xenbus_xs.c:568
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814cda90-ffffffff814cdb41: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e600)
Location: drivers/xen/xenbus/xenbus_xs.c:563
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff8151e600-ffffffff8151e6b2: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154aae0)
Location: drivers/xen/xenbus/xenbus_xs.c:578
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff8154aae0-ffffffff8154ab92: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155f480)
Location: drivers/xen/xenbus/xenbus_xs.c:595
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff8155f480-ffffffff8155f530: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3720)
Location: drivers/xen/xenbus/xenbus_xs.c:598
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff815c3720-ffffffff815c37d0: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fbdb0)
Location: drivers/xen/xenbus/xenbus_xs.c:600
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815fbdb0-ffffffff815fbe62: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616e60)
Location: drivers/xen/xenbus/xenbus_xs.c:600
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81616e60-ffffffff81616f12: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164ab20)
Location: drivers/xen/xenbus/xenbus_xs.c:603
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8164ab20-ffffffff8164abd4: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166cfb0)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8166cfb0-ffffffff8166d064: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d3b0)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff8171d3b0-ffffffff8171d464: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8173a370)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff8173a370-ffffffff8173a424: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171dbf0)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff8171dbf0-ffffffff8171dca4: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179c9a0)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff8179c9a0-ffffffff8179ca54: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d5f00)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff818d5f00-ffffffff818d5fcc: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a283a0)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff81a283a0-ffffffff81a2846c: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a71aa0)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff81a71aa0-ffffffff81a71b6c: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac3c00)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
```
**Symbols:**

```
ffffffff81ac3c00-ffffffff81ac3ccc: xenbus_printf (STB_GLOBAL)
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
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff8000108377a8)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff8000108377a8-ffff800010837888: xenbus_printf (STB_GLOBAL)
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
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81632e20)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81632e20-ffffffff81632ed4: xenbus_printf (STB_GLOBAL)
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
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81660df0)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81660df0-ffffffff81660ea4: xenbus_printf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenbus_printf(struct xenbus_transaction t, const char *dir, const char *node, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167b3d0)
Location: drivers/xen/xenbus/xenbus_xs.c:606
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_event
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8167b3d0-ffffffff8167b484: xenbus_printf (STB_GLOBAL)
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
