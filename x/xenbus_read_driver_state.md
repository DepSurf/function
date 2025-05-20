# Function: <code>xenbus_read_driver_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cb430)
Location: drivers/xen/xenbus/xenbus_client.c:927
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
```
**Symbols:**

```
ffffffff814cb430-ffffffff814cb48b: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151c020)
Location: drivers/xen/xenbus/xenbus_client.c:927
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
```
**Symbols:**

```
ffffffff8151c020-ffffffff8151c07c: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815484f0)
Location: drivers/xen/xenbus/xenbus_client.c:927
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
```
**Symbols:**

```
ffffffff815484f0-ffffffff8154854c: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155c110)
Location: drivers/xen/xenbus/xenbus_client.c:908
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
```
**Symbols:**

```
ffffffff8155c110-ffffffff8155c16c: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c0420)
Location: drivers/xen/xenbus/xenbus_client.c:915
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
```
**Symbols:**

```
ffffffff815c0420-ffffffff815c047c: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f8ab0)
Location: drivers/xen/xenbus/xenbus_client.c:915
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff815f8ab0-ffffffff815f8b0c: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81613b60)
Location: drivers/xen/xenbus/xenbus_client.c:913
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81613b60-ffffffff81613bbc: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816478b0)
Location: drivers/xen/xenbus/xenbus_client.c:913
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:print_device_status
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff816478b0-ffffffff8164790c: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81669d50)
Location: drivers/xen/xenbus/xenbus_client.c:913
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:print_device_status
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff81669d50-ffffffff81669dac: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81719e60)
Location: drivers/xen/xenbus/xenbus_client.c:877
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81719e60-ffffffff81719ebc: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81736f60)
Location: drivers/xen/xenbus/xenbus_client.c:885
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_xdp
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff81736f60-ffffffff81736fbc: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171a990)
Location: drivers/xen/xenbus/xenbus_client.c:885
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_xdp
  - drivers/net/xen-netfront.c:xennet_xdp
```
**Symbols:**

```
ffffffff8171a990-ffffffff8171a9ec: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff817991f0)
Location: drivers/xen/xenbus/xenbus_client.c:880
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_changed
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff817991f0-ffffffff8179924c: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d29a0)
Location: drivers/xen/xenbus/xenbus_client.c:922
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff818d29a0-ffffffff818d2a15: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a249e0)
Location: drivers/xen/xenbus/xenbus_client.c:925
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81a249e0-ffffffff81a24a55: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6df20)
Location: drivers/xen/xenbus/xenbus_client.c:925
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81a6df20-ffffffff81a6df95: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81abffc0)
Location: drivers/xen/xenbus/xenbus_client.c:937
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_probe_node
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_remove
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_bus_close
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
  - drivers/net/xen-netfront.c:xennet_create_dev
```
**Symbols:**

```
ffffffff81abffc0-ffffffff81ac0035: xenbus_read_driver_state (STB_GLOBAL)
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
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff8000108345d0)
Location: drivers/xen/xenbus/xenbus_client.c:913
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:print_device_status
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffff8000108345d0-ffff800010834644: xenbus_read_driver_state (STB_GLOBAL)
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
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8162fbc0)
Location: drivers/xen/xenbus/xenbus_client.c:913
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:print_device_status
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8162fbc0-ffffffff8162fc1c: xenbus_read_driver_state (STB_GLOBAL)
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
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165db90)
Location: drivers/xen/xenbus/xenbus_client.c:913
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:print_device_status
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff8165db90-ffffffff8165dbec: xenbus_read_driver_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum xenbus_state xenbus_read_driver_state(const char *path);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816781a0)
Location: drivers/xen/xenbus/xenbus_client.c:913
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_otherend_changed
  - drivers/xen/xenbus/xenbus_probe_frontend.c:print_device_status
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:xennet_remove
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
  - drivers/net/xen-netfront.c:netfront_probe
```
**Symbols:**

```
ffffffff816781a0-ffffffff816781fc: xenbus_read_driver_state (STB_GLOBAL)
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
