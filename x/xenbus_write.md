# Function: <code>xenbus_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd630)
Location: drivers/xen/xenbus/xenbus_xs.c:447
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814cd630-ffffffff814cd6f7: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e0d0)
Location: drivers/xen/xenbus/xenbus_xs.c:442
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8151e0d0-ffffffff8151e197: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a550)
Location: drivers/xen/xenbus/xenbus_xs.c:442
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff8154a550-ffffffff8154a617: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155f3a0)
Location: drivers/xen/xenbus/xenbus_xs.c:468
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8155f3a0-ffffffff8155f474: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3640)
Location: drivers/xen/xenbus/xenbus_xs.c:471
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815c3640-ffffffff815c3714: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fbce0)
Location: drivers/xen/xenbus/xenbus_xs.c:473
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815fbce0-ffffffff815fbda9: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616d90)
Location: drivers/xen/xenbus/xenbus_xs.c:473
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81616d90-ffffffff81616e59: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164aa50)
Location: drivers/xen/xenbus/xenbus_xs.c:476
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8164aa50-ffffffff8164ab19: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166cee0)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8166cee0-ffffffff8166cfa9: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d2a0)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8171d2a0-ffffffff8171d3a7: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8173a260)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8173a260-ffffffff8173a367: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171dae0)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8171dae0-ffffffff8171dbef: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179c890)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8179c890-ffffffff8179c99f: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d5e00)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff818d5e00-ffffffff818d5efd: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a28290)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a28290-ffffffff81a2838d: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a71990)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a71990-ffffffff81a71a8d: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac3af0)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81ac3af0-ffffffff81ac3bed: xenbus_write (STB_GLOBAL)
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
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff8000108376c0)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff8000108376c0-ffff8000108377a4: xenbus_write (STB_GLOBAL)
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
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81632d50)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81632d50-ffffffff81632e19: xenbus_write (STB_GLOBAL)
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
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81660d20)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81660d20-ffffffff81660de9: xenbus_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenbus_write(struct xenbus_transaction t, const char *dir, const char *node, const char *string);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167b300)
Location: drivers/xen/xenbus/xenbus_xs.c:479
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_printf
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8167b300-ffffffff8167b3c9: xenbus_write (STB_GLOBAL)
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
