# Function: <code>bio_list_merge</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b03d6)
Location: include/linux/bio.h:649
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In drivers/block/xen-blkfront.c (ffffffff81578276)
Location: include/linux/bio.h:649
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_recover
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f3e26)
Location: include/linux/bio.h:601
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In drivers/block/xen-blkfront.c (ffffffff815ce24b)
Location: include/linux/bio.h:601
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140d6a6)
Location: include/linux/bio.h:603
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In drivers/block/xen-blkfront.c (ffffffff815fadff)
Location: include/linux/bio.h:603
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141b40b)
Location: include/linux/bio.h:622
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81425154)
Location: include/linux/bio.h:622
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8160ebc4)
Location: include/linux/bio.h:622
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8144604a)
Location: include/linux/bio.h:626
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8145021c)
Location: include/linux/bio.h:626
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81677444)
Location: include/linux/bio.h:626
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81478fdc)
Location: include/linux/bio.h:669
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81483469)
Location: include/linux/bio.h:669
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In drivers/block/xen-blkfront.c (ffffffff816af393)
Location: include/linux/bio.h:669
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8149723c)
Location: include/linux/bio.h:631
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8149ec33)
Location: include/linux/bio.h:631
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In drivers/block/xen-blkfront.c (ffffffff816d3bc3)
Location: include/linux/bio.h:631
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c4b84)
Location: include/linux/bio.h:627
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814ccd31)
Location: include/linux/bio.h:627
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:627
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff8170f693)
Location: include/linux/bio.h:627
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814dda2a)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814e5f61)
Location: include/linux/bio.h:628
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:628
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81733993)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153d3c3)
Location: include/linux/bio.h:618
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81545198)
Location: include/linux/bio.h:618
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81569b2d)
Location: include/linux/bio.h:618
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/block/xen-blkfront.c (ffffffff817f0cef)
Location: include/linux/bio.h:618
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81559ed3)
Location: include/linux/bio.h:620
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81561621)
Location: include/linux/bio.h:620
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff815843f0)
Location: include/linux/bio.h:620
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/block/xen-blkfront.c (ffffffff818055ff)
Location: include/linux/bio.h:620
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815627e3)
Location: include/linux/bio.h:623
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81569d8b)
Location: include/linux/bio.h:623
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8158b1e5)
Location: include/linux/bio.h:623
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/block/xen-blkfront.c (ffffffff817ea1af)
Location: include/linux/bio.h:623
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c6503)
Location: include/linux/bio.h:584
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff815cd708)
Location: include/linux/bio.h:584
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff815f01e5)
Location: include/linux/bio.h:584
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/block/xen-blkfront.c (ffffffff818768df)
Location: include/linux/bio.h:584
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff816712e0)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81678d85)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff816a12f8)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/block/xen-blkfront.c (ffffffff819beaa2)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172ca80)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff81735225)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff81760128)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/block/xen-blkfront.c (ffffffff81b341e5)
Location: include/linux/bio.h:577
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81768e00)
Location: include/linux/bio.h:590
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff8177179f)
Location: include/linux/bio.h:590
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff8179f258)
Location: include/linux/bio.h:590
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/block/xen-blkfront.c (ffffffff81b876d5)
Location: include/linux/bio.h:590
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817aae30)
Location: include/linux/bio.h:605
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff817b3adf)
Location: include/linux/bio.h:605
Inline: True
Inline callers:
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
  - block/blk-core.c:__submit_bio_noacct
```
```
In block/blk-cgroup.c (ffffffff817e2d28)
Location: include/linux/bio.h:605
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
```
In drivers/block/xen-blkfront.c (ffffffff81bdb585)
Location: include/linux/bio.h:605
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105db4dc)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffff8000105e3538)
Location: include/linux/bio.h:628
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:628
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffff8000109283dc)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c07876c0)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c079083c)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
  - block/blk-core.c:generic_make_request
```
```
In block/blk-cgroup.c (c07b6294)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_async_bio_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076a57c)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (c000000000776e4c)
Location: include/linux/bio.h:628
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:628
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041da50)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffe0004250a6)
Location: include/linux/bio.h:628
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:628
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d600a)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814de541)
Location: include/linux/bio.h:628
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:628
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff816f9993)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6a2a)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814ceee1)
Location: include/linux/bio.h:628
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:628
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d209a)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814da5d1)
Location: include/linux/bio.h:628
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:628
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff81726e53)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eab4a)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - block/bio.c:punt_bios_to_rescuer
```
```
In block/blk-core.c (ffffffff814f32c5)
Location: include/linux/bio.h:628
Inline: True
```
```
In block/blk-cgroup.c (0)
Location: include/linux/bio.h:628
Inline: True
```
```
In drivers/block/xen-blkfront.c (ffffffff817422a3)
Location: include/linux/bio.h:628
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_resume
```
</details>
</li>
</ul>

## Differences
