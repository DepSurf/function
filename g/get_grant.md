# Function: <code>get_grant</code>

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
In drivers/block/xen-blkfront.c (ffffffff81574a85)
Location: drivers/block/xen-blkfront.c:290
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
In drivers/block/xen-blkfront.c (ffffffff815cc4ec)
Location: drivers/block/xen-blkfront.c:350
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
In drivers/block/xen-blkfront.c (ffffffff815f90cc)
Location: drivers/block/xen-blkfront.c:350
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
In drivers/block/xen-blkfront.c (ffffffff8160d26c)
Location: drivers/block/xen-blkfront.c:354
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
In drivers/block/xen-blkfront.c (ffffffff81675aec)
Location: drivers/block/xen-blkfront.c:354
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
In drivers/block/xen-blkfront.c (ffffffff816b110c)
Location: drivers/block/xen-blkfront.c:354
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
In drivers/block/xen-blkfront.c (ffffffff816d144c)
Location: drivers/block/xen-blkfront.c:353
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
In drivers/block/xen-blkfront.c (ffffffff8170ced9)
Location: drivers/block/xen-blkfront.c:353
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
In drivers/block/xen-blkfront.c (ffffffff817311d9)
Location: drivers/block/xen-blkfront.c:353
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
struct grant *get_grant(grant_ref_t *gref_head, long unsigned int gfn, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817edb50)
Location: drivers/block/xen-blkfront.c:364
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
**Symbols:**

```
ffffffff817edb50-ffffffff817edc72: get_grant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct grant *get_grant(grant_ref_t *gref_head, long unsigned int gfn, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81802480)
Location: drivers/block/xen-blkfront.c:364
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
**Symbols:**

```
ffffffff81802480-ffffffff818025a2: get_grant (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e8729)
Location: drivers/block/xen-blkfront.c:364
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
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
In drivers/block/xen-blkfront.c (ffffffff81874988)
Location: drivers/block/xen-blkfront.c:367
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
In drivers/block/xen-blkfront.c (ffffffff819bcc08)
Location: drivers/block/xen-blkfront.c:371
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
In drivers/block/xen-blkfront.c (ffffffff81b322c8)
Location: drivers/block/xen-blkfront.c:374
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b8597d)
Location: drivers/block/xen-blkfront.c:374
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bd988d)
Location: drivers/block/xen-blkfront.c:374
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_setup_rw_req_grant
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
In drivers/block/xen-blkfront.c (ffff800010926d64)
Location: drivers/block/xen-blkfront.c:353
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
In drivers/block/xen-blkfront.c (ffffffff816f70b9)
Location: drivers/block/xen-blkfront.c:368
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
In drivers/block/xen-blkfront.c (ffffffff81724699)
Location: drivers/block/xen-blkfront.c:353
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
In drivers/block/xen-blkfront.c (ffffffff81740339)
Location: drivers/block/xen-blkfront.c:353
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
</ul>
