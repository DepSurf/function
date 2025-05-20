# Function: <code>blkg_get</code>

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
In block/blk-core.c (ffffffff813b8e69)
Location: include/linux/blk-cgroup.h:364
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff813d7d2a)
Location: include/linux/blk-cgroup.h:364
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff813d9bae)
Location: include/linux/blk-cgroup.h:364
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
  - block/blk-throttle.c:tg_dispatch_one_bio
```
```
In block/cfq-iosched.c (ffffffff813df565)
Location: include/linux/blk-cgroup.h:364
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_get_queue
  - block/cfq-iosched.c:cfq_set_request
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
In block/blk-core.c (ffffffff813fcc6c)
Location: include/linux/blk-cgroup.h:364
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff8141d9e9)
Location: include/linux/blk-cgroup.h:364
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8141f148)
Location: include/linux/blk-cgroup.h:364
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/cfq-iosched.c (ffffffff81425ab7)
Location: include/linux/blk-cgroup.h:364
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff81416608)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff81438fa9)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8143a708)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/cfq-iosched.c (ffffffff81444877)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff81423d1c)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff814467d6)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814483aa)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/cfq-iosched.c (ffffffff81453d97)
Location: include/linux/blk-cgroup.h:355
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff8144f496)
Location: include/linux/blk-cgroup.h:351
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8145bf34)
Location: include/linux/blk-cgroup.h:351
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/blk-cgroup.c (ffffffff814733a6)
Location: include/linux/blk-cgroup.h:351
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81477631)
Location: include/linux/blk-cgroup.h:351
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_add_bio_tg
```
```
In block/cfq-iosched.c (ffffffff8147d2fa)
Location: include/linux/blk-cgroup.h:351
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-core.c (ffffffff81481e8e)
Location: include/linux/blk-cgroup.h:369
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8148eb03)
Location: include/linux/blk-cgroup.h:369
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_bio_to_request
```
```
In block/blk-cgroup.c (ffffffff814a7b8c)
Location: include/linux/blk-cgroup.h:369
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814a92e7)
Location: include/linux/blk-cgroup.h:369
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
```
In block/cfq-iosched.c (ffffffff814b426e)
Location: include/linux/blk-cgroup.h:369
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_set_request
  - block/cfq-iosched.c:cfq_get_queue
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
In block/blk-cgroup.c (ffffffff814c2643)
Location: include/linux/blk-cgroup.h:488
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814c4657)
Location: include/linux/blk-cgroup.h:488
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff814f0c67)
Location: include/linux/blk-cgroup.h:495
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f2e18)
Location: include/linux/blk-cgroup.h:495
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff8150a243)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8150c3b8)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff8156b453)
Location: include/linux/blk-cgroup.h:466
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8156da31)
Location: include/linux/blk-cgroup.h:466
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
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
In block/blk-cgroup.c (ffffffff81585a69)
Location: include/linux/blk-cgroup.h:456
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81587f4d)
Location: include/linux/blk-cgroup.h:456
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
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
In block/blk-cgroup.c (ffffffff8158c439)
Location: include/linux/blk-cgroup.h:456
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8158ed9d)
Location: include/linux/blk-cgroup.h:456
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
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
In block/blk-cgroup.c (ffffffff815f1a69)
Location: include/linux/blk-cgroup.h:461
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff815f4dfd)
Location: include/linux/blk-cgroup.h:461
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
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
In block/blk-cgroup.c (ffffffff816a3888)
Location: block/blk-cgroup.h:336
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff816a69fe)
Location: block/blk-cgroup.h:336
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_add_bio_tg
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
In block/blk-cgroup.c (ffffffff81762569)
Location: block/blk-cgroup.h:320
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81765924)
Location: block/blk-cgroup.h:320
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff817a1f8e)
Location: block/blk-cgroup.h:321
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817a49e4)
Location: block/blk-cgroup.h:321
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff817e5adb)
Location: block/blk-cgroup.h:320
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff817e85b4)
Location: block/blk-cgroup.h:320
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffff80001060d8f0)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffff80001061061c)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (c07b8488)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c07ba82c)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (c0000000007aaa9c)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (c0000000007ad6bc)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffe00044612c)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffe000447e24)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff81502823)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81504998)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff814f2fd3)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814f4e58)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff814fe8b3)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81500a28)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
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
In block/blk-cgroup.c (ffffffff81517c77)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81519983)
Location: include/linux/blk-cgroup.h:497
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_qnode_add_bio
```
</details>
</li>
</ul>

## Differences
