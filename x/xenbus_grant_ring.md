# Function: <code>xenbus_grant_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc300)
Location: drivers/xen/xenbus/xenbus_client.c:380
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff814cc300-ffffffff814cc44b: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151cee0)
Location: drivers/xen/xenbus/xenbus_client.c:380
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8151cee0-ffffffff8151d019: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815493b0)
Location: drivers/xen/xenbus/xenbus_client.c:380
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
```
**Symbols:**

```
ffffffff815493b0-ffffffff815494e9: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d320)
Location: drivers/xen/xenbus/xenbus_client.c:361
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8155d320-ffffffff8155d471: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1620)
Location: drivers/xen/xenbus/xenbus_client.c:361
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815c1620-ffffffff815c1771: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f96e0)
Location: drivers/xen/xenbus/xenbus_client.c:361
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff815f96e0-ffffffff815f981d: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816147a0)
Location: drivers/xen/xenbus/xenbus_client.c:359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff816147a0-ffffffff816148dd: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648480)
Location: drivers/xen/xenbus/xenbus_client.c:359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81648480-ffffffff816485c8: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166a920)
Location: drivers/xen/xenbus/xenbus_client.c:359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8166a920-ffffffff8166aa68: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171aad0)
Location: drivers/xen/xenbus/xenbus_client.c:375
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff8171aad0-ffffffff8171ac63: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81737c40)
Location: drivers/xen/xenbus/xenbus_client.c:378
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff81737c40-ffffffff81737dd3: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b660)
Location: drivers/xen/xenbus/xenbus_client.c:378
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff8171b660-ffffffff8171b817: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179a0e0)
Location: drivers/xen/xenbus/xenbus_client.c:378
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:setup_blkring
  - drivers/net/xen-netfront.c:setup_netfront
  - drivers/net/xen-netfront.c:setup_netfront
```
**Symbols:**

```
ffffffff8179a0e0-ffffffff8179a2a7: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff800010834cb8)
Location: drivers/xen/xenbus/xenbus_client.c:359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffff800010834cb8-ffff800010834df4: xenbus_grant_ring (STB_GLOBAL)
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
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630790)
Location: drivers/xen/xenbus/xenbus_client.c:359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff81630790-ffffffff816308d8: xenbus_grant_ring (STB_GLOBAL)
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
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165e760)
Location: drivers/xen/xenbus/xenbus_client.c:359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff8165e760-ffffffff8165e8a8: xenbus_grant_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xenbus_grant_ring(struct xenbus_device *dev, void *vaddr, unsigned int nr_pages, grant_ref_t *grefs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816792a0)
Location: drivers/xen/xenbus/xenbus_client.c:359
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
  - drivers/net/xen-netfront.c:talk_to_netback
  - drivers/net/xen-netfront.c:talk_to_netback
```
**Symbols:**

```
ffffffff816792a0-ffffffff816793e8: xenbus_grant_ring (STB_GLOBAL)
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
