# Function: <code>xenbus_dev_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cb1c0)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff814cb1c0-ffffffff814cb225: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151bda0)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff8151bda0-ffffffff8151be05: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81548270)
Location: drivers/xen/xenbus/xenbus_client.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81548270-ffffffff815482d5: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155c010)
Location: drivers/xen/xenbus/xenbus_client.c:299
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff8155c010-ffffffff8155c076: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c0320)
Location: drivers/xen/xenbus/xenbus_client.c:299
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff815c0320-ffffffff815c0386: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f89b0)
Location: drivers/xen/xenbus/xenbus_client.c:299
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff815f89b0-ffffffff815f8a15: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81613a60)
Location: drivers/xen/xenbus/xenbus_client.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81613a60-ffffffff81613ac5: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816477d0)
Location: drivers/xen/xenbus/xenbus_client.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff816477d0-ffffffff81647835: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81669c70)
Location: drivers/xen/xenbus/xenbus_client.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff81669c70-ffffffff81669cd5: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81719d80)
Location: drivers/xen/xenbus/xenbus_client.c:313
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkfront_closing
```
**Symbols:**

```
ffffffff81719d80-ffffffff81719de5: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81736e80)
Location: drivers/xen/xenbus/xenbus_client.c:316
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkfront_closing
```
**Symbols:**

```
ffffffff81736e80-ffffffff81736ee5: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171a8b0)
Location: drivers/xen/xenbus/xenbus_client.c:316
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff8171a8b0-ffffffff8171a915: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81799110)
Location: drivers/xen/xenbus/xenbus_client.c:316
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
**Symbols:**

```
ffffffff81799110-ffffffff81799175: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d25f0)
Location: drivers/xen/xenbus/xenbus_client.c:316
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
**Symbols:**

```
ffffffff818d25f0-ffffffff818d2671: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a245c0)
Location: drivers/xen/xenbus/xenbus_client.c:316
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
**Symbols:**

```
ffffffff81a245c0-ffffffff81a24641: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6db00)
Location: drivers/xen/xenbus/xenbus_client.c:316
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
**Symbols:**

```
ffffffff81a6db00-ffffffff81a6db81: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81abfba0)
Location: drivers/xen/xenbus/xenbus_client.c:325
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
```
**Symbols:**

```
ffffffff81abfba0-ffffffff81abfc21: xenbus_dev_error (STB_GLOBAL)
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
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff8000108344a0)
Location: drivers/xen/xenbus/xenbus_client.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffff8000108344a0-ffff800010834540: xenbus_dev_error (STB_GLOBAL)
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
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8162fae0)
Location: drivers/xen/xenbus/xenbus_client.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkfront_freeze
  - drivers/block/xen-blkfront.c:blkfront_freeze
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff8162fae0-ffffffff8162fb45: xenbus_dev_error (STB_GLOBAL)
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
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165dab0)
Location: drivers/xen/xenbus/xenbus_client.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff8165dab0-ffffffff8165db15: xenbus_dev_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xenbus_dev_error(struct xenbus_device *dev, int err, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff816780c0)
Location: drivers/xen/xenbus/xenbus_client.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_unmap_ring_vfree_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_free_evtchn
  - drivers/xen/xenbus/xenbus_probe.c:xenbus_dev_probe
  - drivers/block/xen-blkfront.c:blkback_changed
```
**Symbols:**

```
ffffffff816780c0-ffffffff81678125: xenbus_dev_error (STB_GLOBAL)
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
