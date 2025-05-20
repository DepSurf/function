# Function: <code>get_indirect_grant</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81574ba6)
Location: drivers/block/xen-blkfront.c:314
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815cc607)
Location: drivers/block/xen-blkfront.c:375
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f91e7)
Location: drivers/block/xen-blkfront.c:375
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160d3d4)
Location: drivers/block/xen-blkfront.c:379
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81675c54)
Location: drivers/block/xen-blkfront.c:379
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816b127c)
Location: drivers/block/xen-blkfront.c:379
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816d15bc)
Location: drivers/block/xen-blkfront.c:378
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
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
In drivers/block/xen-blkfront.c (ffffffff8170d04c)
Location: drivers/block/xen-blkfront.c:378
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
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
In drivers/block/xen-blkfront.c (ffffffff8173134c)
Location: drivers/block/xen-blkfront.c:378
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct grant *get_indirect_grant(grant_ref_t *gref_head, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817ed9f0)
Location: drivers/block/xen-blkfront.c:389
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
**Symbols:**

```
ffffffff817ed9f0-ffffffff817edb47: get_indirect_grant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct grant *get_indirect_grant(grant_ref_t *gref_head, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81802320)
Location: drivers/block/xen-blkfront.c:389
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
**Symbols:**

```
ffffffff81802320-ffffffff81802477: get_indirect_grant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct grant *get_indirect_grant(grant_ref_t *gref_head, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e6e90)
Location: drivers/block/xen-blkfront.c:389
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
**Symbols:**

```
ffffffff817e6e90-ffffffff817e6fdb: get_indirect_grant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81874b24)
Location: drivers/block/xen-blkfront.c:392
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff819bcd31)
Location: drivers/block/xen-blkfront.c:396
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b323f1)
Location: drivers/block/xen-blkfront.c:399
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct grant *get_indirect_grant(grant_ref_t *gref_head, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b83eb0)
Location: drivers/block/xen-blkfront.c:399
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
**Symbols:**

```
ffffffff81b83eb0-ffffffff81b84061: get_indirect_grant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct grant *get_indirect_grant(grant_ref_t *gref_head, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd7de0)
Location: drivers/block/xen-blkfront.c:399
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
**Symbols:**

```
ffffffff81bd7de0-ffffffff81bd7f91: get_indirect_grant (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffff800010926f14)
Location: drivers/block/xen-blkfront.c:378
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
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
In drivers/block/xen-blkfront.c (ffffffff816f722c)
Location: drivers/block/xen-blkfront.c:393
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
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
In drivers/block/xen-blkfront.c (ffffffff8172480c)
Location: drivers/block/xen-blkfront.c:378
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
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
In drivers/block/xen-blkfront.c (ffffffff817404cd)
Location: drivers/block/xen-blkfront.c:378
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
