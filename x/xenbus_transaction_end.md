# Function: <code>xenbus_transaction_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814ce480)
Location: drivers/xen/xenbus/xenbus_xs.c:526
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814ce480-ffffffff814ce4f2: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151f040)
Location: drivers/xen/xenbus/xenbus_xs.c:521
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8151f040-ffffffff8151f0b2: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154b510)
Location: drivers/xen/xenbus/xenbus_xs.c:521
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff8154b510-ffffffff8154b582: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155f2a0)
Location: drivers/xen/xenbus/xenbus_xs.c:543
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8155f2a0-ffffffff8155f39f: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c35d0)
Location: drivers/xen/xenbus/xenbus_xs.c:546
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815c35d0-ffffffff815c3633: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fbc70)
Location: drivers/xen/xenbus/xenbus_xs.c:548
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815fbc70-ffffffff815fbcd3: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616d20)
Location: drivers/xen/xenbus/xenbus_xs.c:548
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81616d20-ffffffff81616d83: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164a9e0)
Location: drivers/xen/xenbus/xenbus_xs.c:551
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_free
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8164a9e0-ffffffff8164aa43: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166ce70)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8166ce70-ffffffff8166ced3: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171ce00)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8171ce00-ffffffff8171ce63: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81739dc0)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81739dc0-ffffffff81739e23: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d6f0)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8171d6f0-ffffffff8171d753: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179c4a0)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8179c4a0-ffffffff8179c503: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d5a60)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff818d5a60-ffffffff818d5acf: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a27eb0)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a27eb0-ffffffff81a27f1f: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a715b0)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a715b0-ffffffff81a7161f: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac3710)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_switch_state
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81ac3710-ffffffff81ac377f: xenbus_transaction_end (STB_GLOBAL)
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
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff800010837630)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff800010837630-ffff8000108376bc: xenbus_transaction_end (STB_GLOBAL)
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
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81632ce0)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81632ce0-ffffffff81632d43: xenbus_transaction_end (STB_GLOBAL)
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
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81660cb0)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81660cb0-ffffffff81660d13: xenbus_transaction_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenbus_transaction_end(struct xenbus_transaction t, int abort);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167b290)
Location: drivers/xen/xenbus/xenbus_xs.c:554
Inline: False
Direct callers:
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:sysrq_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_worker
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:write_per_ring_nodes
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8167b290-ffffffff8167b2f3: xenbus_transaction_end (STB_GLOBAL)
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
