# Function: <code>__xenbus_map_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, phys_addr_t *addrs, unsigned int flags, bool *leaked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cbcc0)
Location: drivers/xen/xenbus/xenbus_client.c:479
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff814cbcc0-ffffffff814cbff8: __xenbus_map_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, phys_addr_t *addrs, unsigned int flags, bool *leaked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151c8a0)
Location: drivers/xen/xenbus/xenbus_client.c:479
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8151c8a0-ffffffff8151cbde: __xenbus_map_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, phys_addr_t *addrs, unsigned int flags, bool *leaked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81548d70)
Location: drivers/xen/xenbus/xenbus_client.c:479
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff81548d70-ffffffff815490ae: __xenbus_map_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155cfaa)
Location: drivers/xen/xenbus/xenbus_client.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
```
**Symbols:**

```
ffffffff8155cb30-ffffffff8155ce18: __xenbus_map_ring.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1502)
Location: drivers/xen/xenbus/xenbus_client.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff815c0e30-ffffffff815c1118: __xenbus_map_ring.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f9d2f)
Location: drivers/xen/xenbus/xenbus_client.c:460
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff815f90e0-ffffffff815f93d4: __xenbus_map_ring.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8161502f)
Location: drivers/xen/xenbus/xenbus_client.c:458
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81614190-ffffffff81614484: __xenbus_map_ring.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648c7d)
Location: drivers/xen/xenbus/xenbus_client.c:458
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81647ec0-ffffffff81648178: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166b11d)
Location: drivers/xen/xenbus/xenbus_client.c:458
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff8166a360-ffffffff8166a618: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171b18d)
Location: drivers/xen/xenbus/xenbus_client.c:499
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff8171a470-ffffffff8171a6ae: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8173830d)
Location: drivers/xen/xenbus/xenbus_client.c:502
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff817375c0-ffffffff81737806: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8171bd3d)
Location: drivers/xen/xenbus/xenbus_client.c:502
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff8171b000-ffffffff8171b244: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8179aa5d)
Location: drivers/xen/xenbus/xenbus_client.c:500
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff817999d0-ffffffff81799df0: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff818d329d)
Location: drivers/xen/xenbus/xenbus_client.c:542
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff818d2dc0-ffffffff818d3207: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a2540d)
Location: drivers/xen/xenbus/xenbus_client.c:545
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81a24f20-ffffffff81a25367: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6e9bd)
Location: drivers/xen/xenbus/xenbus_client.c:545
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81a6e4d0-ffffffff81a6e91b: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac0a5d)
Location: drivers/xen/xenbus/xenbus_client.c:555
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_hvm
```
**Symbols:**

```
ffffffff81ac0570-ffffffff81ac09bb: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff8000108353cc)
Location: drivers/xen/xenbus/xenbus_client.c:458
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffff800010834e98-ffff800010835154: __xenbus_map_ring.part.0.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630f8d)
Location: drivers/xen/xenbus/xenbus_client.c:458
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff816301d0-ffffffff81630488: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165ef5d)
Location: drivers/xen/xenbus/xenbus_client.c:458
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff8165e1a0-ffffffff8165e458: __xenbus_map_ring.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8167918d)
Location: drivers/xen/xenbus/xenbus_client.c:458
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_pv
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc_hvm
```
**Symbols:**

```
ffffffff81678b00-ffffffff81678db8: __xenbus_map_ring.part.0 (STB_LOCAL)
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
</ul>
