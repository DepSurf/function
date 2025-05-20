# Function: <code>setup_blkring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81575510)
Location: drivers/block/xen-blkfront.c:1410
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81575510-ffffffff81575943: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815c9070)
Location: drivers/block/xen-blkfront.c:1658
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff815c9070-ffffffff815c949a: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f5dc0)
Location: drivers/block/xen-blkfront.c:1657
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff815f5dc0-ffffffff815f61ea: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160a100)
Location: drivers/block/xen-blkfront.c:1670
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff8160a100-ffffffff8160a514: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816729d0)
Location: drivers/block/xen-blkfront.c:1670
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff816729d0-ffffffff81672de4: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816ae4c0)
Location: drivers/block/xen-blkfront.c:1670
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff816ae4c0-ffffffff816ae8c8: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816cf400)
Location: drivers/block/xen-blkfront.c:1669
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff816cf400-ffffffff816cf808: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8170e8d9)
Location: drivers/block/xen-blkfront.c:1669
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81732bd9)
Location: drivers/block/xen-blkfront.c:1669
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817efdd0)
Location: drivers/block/xen-blkfront.c:1679
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff817efdd0-ffffffff817f022c: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff818046d0)
Location: drivers/block/xen-blkfront.c:1680
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff818046d0-ffffffff81804b3c: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e9270)
Location: drivers/block/xen-blkfront.c:1680
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff817e9270-ffffffff817e96d9: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81875930)
Location: drivers/block/xen-blkfront.c:1683
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81875930-ffffffff81875e5a: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff819bdb90)
Location: drivers/block/xen-blkfront.c:1677
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff819bdb90-ffffffff819bdfe1: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b33280)
Location: drivers/block/xen-blkfront.c:1680
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81b33280-ffffffff81b336d1: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b867d0)
Location: drivers/block/xen-blkfront.c:1681
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81b867d0-ffffffff81b86c2f: setup_blkring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int setup_blkring(struct xenbus_device *dev, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bda680)
Location: drivers/block/xen-blkfront.c:1681
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
**Symbols:**

```
ffffffff81bda680-ffffffff81bdaadf: setup_blkring (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff8000109277a4)
Location: drivers/block/xen-blkfront.c:1669
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f8b89)
Location: drivers/block/xen-blkfront.c:1694
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81726099)
Location: drivers/block/xen-blkfront.c:1669
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817414e9)
Location: drivers/block/xen-blkfront.c:1669
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:talk_to_blkback
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blkfront_ring_info *rinfo</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blkfront_info *info</code>
</li>
</ul>
</details>
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
