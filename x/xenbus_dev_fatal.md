# Function: <code>xenbus_dev_fatal</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cba50)
Location: drivers/xen/xenbus/xenbus_client.c:339
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814cba50-ffffffff814cbad6: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151c630)
Location: drivers/xen/xenbus/xenbus_client.c:339
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8151c630-ffffffff8151c6b6: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81548b00)
Location: drivers/xen/xenbus/xenbus_client.c:339
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81548b00-ffffffff81548b86: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155c8c0)
Location: drivers/xen/xenbus/xenbus_client.c:320
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8155c8c0-ffffffff8155c943: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c0bc0)
Location: drivers/xen/xenbus/xenbus_client.c:320
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff815c0bc0-ffffffff815c0c43: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f8e70)
Location: drivers/xen/xenbus/xenbus_client.c:320
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff815f8e70-ffffffff815f8ef6: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81613f20)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81613f20-ffffffff81613fa6: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81647c60)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81647c60-ffffffff81647cea: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166a100)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8166a100-ffffffff8166a18a: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171a2f0)
Location: drivers/xen/xenbus/xenbus_client.c:334
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8171a2f0-ffffffff8171a378: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737430)
Location: drivers/xen/xenbus/xenbus_client.c:337
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81737430-ffffffff817374b8: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171ae70)
Location: drivers/xen/xenbus/xenbus_client.c:337
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8171ae70-ffffffff8171aef8: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81799840)
Location: drivers/xen/xenbus/xenbus_client.c:337
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81799840-ffffffff817998c8: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d2700)
Location: drivers/xen/xenbus/xenbus_client.c:337
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff818d2700-ffffffff818d2798: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a246f0)
Location: drivers/xen/xenbus/xenbus_client.c:337
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81a246f0-ffffffff81a24788: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6dc30)
Location: drivers/xen/xenbus/xenbus_client.c:337
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81a6dc30-ffffffff81a6dcc8: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81abfcd0)
Location: drivers/xen/xenbus/xenbus_client.c:346
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:write_queue_xenstore_keys
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81abfcd0-ffffffff81abfd68: xenbus_dev_fatal (STB_GLOBAL)
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
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff800010834a78)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffff800010834a78-ffff800010834b38: xenbus_dev_fatal (STB_GLOBAL)
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
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8162ff70)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8162ff70-ffffffff8162fffa: xenbus_dev_fatal (STB_GLOBAL)
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
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165df40)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8165df40-ffffffff8165dfca: xenbus_dev_fatal (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xenbus_dev_fatal(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816788a0)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_alloc_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_pathfmt
  - drivers/xen/xenbus/xenbus_client.c:xenbus_watch_path
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff816788a0-ffffffff8167892a: xenbus_dev_fatal (STB_GLOBAL)
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
