# Function: <code>xenbus_setup_ring</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_setup_ring(struct xenbus_device *dev, gfp_t gfp, void **vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d3be0)
Location: drivers/xen/xenbus/xenbus_client.c:379
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff818d3be0-ffffffff818d3df6: xenbus_setup_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_setup_ring(struct xenbus_device *dev, gfp_t gfp, void **vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a25dd0)
Location: drivers/xen/xenbus/xenbus_client.c:379
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81a25dd0-ffffffff81a26000: xenbus_setup_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_setup_ring(struct xenbus_device *dev, gfp_t gfp, void **vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6f380)
Location: drivers/xen/xenbus/xenbus_client.c:379
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81a6f380-ffffffff81a6f5b0: xenbus_setup_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_setup_ring(struct xenbus_device *dev, gfp_t gfp, void **vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac1480)
Location: drivers/xen/xenbus/xenbus_client.c:388
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81ac1480-ffffffff81ac16b0: xenbus_setup_ring (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
