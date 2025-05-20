# Function: <code>gnttab_alloc_grant_references</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c5200)
Location: drivers/xen/grant-table.c:486
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814c5200-ffffffff814c5227: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81515980)
Location: drivers/xen/grant-table.c:485
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81515980-ffffffff815159a7: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81541e10)
Location: drivers/xen/grant-table.c:485
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff81541e10-ffffffff81541e37: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81555c50)
Location: drivers/xen/grant-table.c:486
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81555c50-ffffffff81555c77: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b98a0)
Location: drivers/xen/grant-table.c:571
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815b98a0-ffffffff815b98c7: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f3230)
Location: drivers/xen/grant-table.c:571
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815f3230-ffffffff815f3257: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160d800)
Location: drivers/xen/grant-table.c:575
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff8160d800-ffffffff8160d827: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81641260)
Location: drivers/xen/grant-table.c:575
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81641260-ffffffff81641287: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81663c20)
Location: drivers/xen/grant-table.c:575
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81663c20-ffffffff81663c47: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81712e20)
Location: drivers/xen/grant-table.c:574
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_init_queue
  - drivers/net/xen-netfront.c:xennet_init_queue
```
**Symbols:**

```
ffffffff81712e20-ffffffff81712e4a: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172fc20)
Location: drivers/xen/grant-table.c:574
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_init_queue
  - drivers/net/xen-netfront.c:xennet_init_queue
```
**Symbols:**

```
ffffffff8172fc20-ffffffff8172fc4a: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81713730)
Location: drivers/xen/grant-table.c:574
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81713730-ffffffff8171375a: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81790380)
Location: drivers/xen/grant-table.c:581
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_grant_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff81790380-ffffffff817903aa: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff818c8680)
Location: drivers/xen/grant-table.c:632
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff818c8680-ffffffff818c86b2: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a190a0)
Location: drivers/xen/grant-table.c:632
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff81a190a0-ffffffff81a190d2: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a62120)
Location: drivers/xen/grant-table.c:650
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff81a62120-ffffffff81a62152: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab4950)
Location: drivers/xen/grant-table.c:648
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_setup_ring
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
```
**Symbols:**

```
ffffffff81ab4950-ffffffff81ab4982: gnttab_alloc_grant_references (STB_GLOBAL)
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
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082dfd0)
Location: drivers/xen/grant-table.c:575
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffff80001082dfd0-ffff80001082e018: gnttab_alloc_grant_references (STB_GLOBAL)
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
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81629a90)
Location: drivers/xen/grant-table.c:575
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81629a90-ffffffff81629ab7: gnttab_alloc_grant_references (STB_GLOBAL)
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
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81657a60)
Location: drivers/xen/grant-table.c:575
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81657a60-ffffffff81657a87: gnttab_alloc_grant_references (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gnttab_alloc_grant_references(u16 count, grant_ref_t *head);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81672060)
Location: drivers/xen/grant-table.c:575
Inline: False
Direct callers:
  - drivers/tty/hvc/hvc_xen.c:xencons_connect_backend
  - drivers/block/xen-blkfront.c:blkif_queue_rw_req
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_create_queues
```
**Symbols:**

```
ffffffff81672060-ffffffff81672087: gnttab_alloc_grant_references (STB_GLOBAL)
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
