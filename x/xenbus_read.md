# Function: <code>xenbus_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd4f0)
Location: drivers/xen/xenbus/xenbus_xs.c:428
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814cd4f0-ffffffff814cd542: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e070)
Location: drivers/xen/xenbus/xenbus_xs.c:423
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8151e070-ffffffff8151e0cf: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a4f0)
Location: drivers/xen/xenbus/xenbus_xs.c:423
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff8154a4f0-ffffffff8154a54f: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155eea0)
Location: drivers/xen/xenbus/xenbus_xs.c:449
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8155eea0-ffffffff8155eeff: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c31d0)
Location: drivers/xen/xenbus/xenbus_xs.c:452
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815c31d0-ffffffff815c322f: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fb870)
Location: drivers/xen/xenbus/xenbus_xs.c:454
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815fb870-ffffffff815fb8c5: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616920)
Location: drivers/xen/xenbus/xenbus_xs.c:454
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81616920-ffffffff81616975: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164a5d0)
Location: drivers/xen/xenbus/xenbus_xs.c:457
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8164a5d0-ffffffff8164a632: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166ca60)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8166ca60-ffffffff8166cac2: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171cf1d)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8171cbb0-ffffffff8171cc42: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81739edd)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81739b70-ffffffff81739c02: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d80d)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8171d4a0-ffffffff8171d532: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179c5bd)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8179c250-ffffffff8179c2e2: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d5b8a)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff818d5880-ffffffff818d58f7: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a27fea)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a27c90-ffffffff81a27d07: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a716ea)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81a71390-ffffffff81a71407: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac384a)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81ac34f0-ffffffff81ac3567: xenbus_read (STB_GLOBAL)
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
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff800010837138)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff800010837138-ffff8000108371c4: xenbus_read (STB_GLOBAL)
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
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816328d0)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff816328d0-ffffffff81632932: xenbus_read (STB_GLOBAL)
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
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816608a0)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff816608a0-ffffffff81660902: xenbus_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xenbus_read(struct xenbus_transaction t, const char *dir, const char *node, unsigned int *len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167ae80)
Location: drivers/xen/xenbus/xenbus_xs.c:460
Inline: False
Direct callers:
  - drivers/xen/manage.c:shutdown_handler
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/xen/sys-hypervisor.c:uuid_show
  - drivers/block/xen-blkfront.c:blkfront_probe
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8167ae80-ffffffff8167aee2: xenbus_read (STB_GLOBAL)
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
