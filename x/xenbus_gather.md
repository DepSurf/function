# Function: <code>xenbus_gather</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cdb50)
Location: drivers/xen/xenbus/xenbus_xs.c:591
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff814cdb50-ffffffff814cdcaa: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e6c0)
Location: drivers/xen/xenbus/xenbus_xs.c:586
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff8151e6c0-ffffffff8151e820: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154aba0)
Location: drivers/xen/xenbus/xenbus_xs.c:601
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff8154aba0-ffffffff8154ad00: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155f010)
Location: drivers/xen/xenbus/xenbus_xs.c:618
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff8155f010-ffffffff8155f166: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c3340)
Location: drivers/xen/xenbus/xenbus_xs.c:621
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff815c3340-ffffffff815c3496: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fb9e0)
Location: drivers/xen/xenbus/xenbus_xs.c:623
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff815fb9e0-ffffffff815fbb37: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616a90)
Location: drivers/xen/xenbus/xenbus_xs.c:623
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff81616a90-ffffffff81616be7: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164a750)
Location: drivers/xen/xenbus/xenbus_xs.c:626
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff8164a750-ffffffff8164a8aa: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166cbe0)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff8166cbe0-ffffffff8166cd3a: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171ce70)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff8171ce70-ffffffff8171d062: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81739e30)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81739e30-ffffffff8173a022: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d760)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff8171d760-ffffffff8171d952: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179c510)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff8179c510-ffffffff8179c702: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d5ad0)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff818d5ad0-ffffffff818d5c7b: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a27f30)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81a27f30-ffffffff81a280db: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a71630)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81a71630-ffffffff81a717db: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac3790)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_read_otherend_details
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
```
**Symbols:**

```
ffffffff81ac3790-ffffffff81ac393b: xenbus_gather (STB_GLOBAL)
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
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff800010837330)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffff800010837330-ffff8000108374b4: xenbus_gather (STB_GLOBAL)
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
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81632a50)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff81632a50-ffffffff81632baa: xenbus_gather (STB_GLOBAL)
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
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81660a20)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff81660a20-ffffffff81660b7a: xenbus_gather (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenbus_gather(struct xenbus_transaction t, const char *dir, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167b000)
Location: drivers/xen/xenbus/xenbus_xs.c:629
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_read_driver_state
  - drivers/xen/xenbus/xenbus_probe_backend.c:backend_bus_id
  - drivers/block/xen-blkfront.c:blkfront_connect
  - drivers/block/xen-blkfront.c:blkfront_gather_backend_features
```
**Symbols:**

```
ffffffff8167b000-ffffffff8167b15a: xenbus_gather (STB_GLOBAL)
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
