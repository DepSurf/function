# Function: <code>xenbus_read_unsigned</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154b9f9)
Location: drivers/xen/xenbus/xenbus_xs.c:563
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff8154aa80-ffffffff8154aada: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155fd08)
Location: drivers/xen/xenbus/xenbus_xs.c:580
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
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
ffffffff8155efb0-ffffffff8155f00b: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3fa8)
Location: drivers/xen/xenbus/xenbus_xs.c:583
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
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
ffffffff815c32e0-ffffffff815c333b: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fc60b)
Location: drivers/xen/xenbus/xenbus_xs.c:585
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
ffffffff815fb980-ffffffff815fb9db: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816176bb)
Location: drivers/xen/xenbus/xenbus_xs.c:585
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
ffffffff81616a30-ffffffff81616a8b: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164b364)
Location: drivers/xen/xenbus/xenbus_xs.c:588
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
ffffffff8164a6f0-ffffffff8164a74a: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166d7f4)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
ffffffff8166cb80-ffffffff8166cbda: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d238)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff8171d190-ffffffff8171d1e9: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8173a1f8)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff8173a150-ffffffff8173a1a9: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171e509)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff8171da80-ffffffff8171dad9: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179d2b9)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff8179c830-ffffffff8179c889: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d69ac)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff818d5d80-ffffffff818d5df2: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a28efd)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff81a28200-ffffffff81a28272: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a725fd)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff81a71900-ffffffff81a71972: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac475d)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:negotiate_mq
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
  - drivers/net/xen-netfront.c:xennet_fix_features
```
**Symbols:**

```
ffffffff81ac3a60-ffffffff81ac3ad2: xenbus_read_unsigned (STB_GLOBAL)
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
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff8000108381c8)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
ffff8000108372b0-ffff80001083732c: xenbus_read_unsigned (STB_GLOBAL)
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
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81633664)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
ffffffff816329f0-ffffffff81632a4a: xenbus_read_unsigned (STB_GLOBAL)
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
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81661634)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
ffffffff816609c0-ffffffff81660a1a: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int xenbus_read_unsigned(const char *dir, const char *node, unsigned int default_val);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167bc04)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_backend.c:xenbus_dev_is_online
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
ffffffff8167afa0-ffffffff8167affa: xenbus_read_unsigned (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
