# Function: <code>blkg_put</code>

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
In block/blk-core.c (ffffffff813b6691)
Location: include/linux/blk-cgroup.h:376
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff813d7e37)
Location: include/linux/blk-cgroup.h:376
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
```
```
In block/blk-throttle.c (ffffffff813d96fe)
Location: include/linux/blk-cgroup.h:376
Inline: True
Inline callers:
  - block/blk-throttle.c:throtl_pop_queued
  - block/blk-throttle.c:tg_dispatch_one_bio
```
```
In block/cfq-iosched.c (ffffffff813df58c)
Location: include/linux/blk-cgroup.h:376
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
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
In block/blk-core.c (ffffffff813fd219)
Location: include/linux/blk-cgroup.h:376
Inline: True
Inline callers:
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff8141e092)
Location: include/linux/blk-cgroup.h:376
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814210ea)
Location: include/linux/blk-cgroup.h:376
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/cfq-iosched.c (ffffffff81425ade)
Location: include/linux/blk-cgroup.h:376
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
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
In block/blk-core.c (ffffffff81414fc2)
Location: include/linux/blk-cgroup.h:367
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff81439652)
Location: include/linux/blk-cgroup.h:367
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8143c354)
Location: include/linux/blk-cgroup.h:367
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/cfq-iosched.c (ffffffff8144489e)
Location: include/linux/blk-cgroup.h:367
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
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
In block/blk-core.c (ffffffff81423565)
Location: include/linux/blk-cgroup.h:367
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-cgroup.c (ffffffff81446e7f)
Location: include/linux/blk-cgroup.h:367
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff8144af58)
Location: include/linux/blk-cgroup.h:367
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/cfq-iosched.c (ffffffff81453dba)
Location: include/linux/blk-cgroup.h:367
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
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
In block/blk-core.c (ffffffff8144ef05)
Location: include/linux/blk-cgroup.h:363
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8145aca4)
Location: include/linux/blk-cgroup.h:363
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-cgroup.c (ffffffff81473a5f)
Location: include/linux/blk-cgroup.h:363
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff81477465)
Location: include/linux/blk-cgroup.h:363
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/cfq-iosched.c (ffffffff8147d31d)
Location: include/linux/blk-cgroup.h:363
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
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
In block/blk-core.c (ffffffff81481acc)
Location: include/linux/blk-cgroup.h:381
Inline: True
Inline callers:
  - block/blk-core.c:__blk_put_request
  - block/blk-core.c:get_request
  - block/blk-core.c:get_request
```
```
In block/blk-mq.c (ffffffff8148dd53)
Location: include/linux/blk-cgroup.h:381
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_request
```
```
In block/blk-cgroup.c (ffffffff814a7e2f)
Location: include/linux/blk-cgroup.h:381
Inline: True
Inline callers:
  - block/blk-cgroup.c:__blkg_release_rcu
  - block/blk-cgroup.c:blkg_destroy
  - block/blk-cgroup.c:blkg_create
```
```
In block/blk-throttle.c (ffffffff814abbab)
Location: include/linux/blk-cgroup.h:381
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
```
In block/cfq-iosched.c (ffffffff814b4293)
Location: include/linux/blk-cgroup.h:381
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_put_queue
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
In block/bio.c (ffffffff8149860c)
Location: include/linux/blk-cgroup.h:535
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-cgroup.c (ffffffff814c32aa)
Location: include/linux/blk-cgroup.h:535
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814c5f9d)
Location: include/linux/blk-cgroup.h:535
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff814c64a6)
Location: include/linux/blk-cgroup.h:542
Inline: True
Inline callers:
  - block/bio.c:bio_endio
  - block/bio.c:bio_reset
  - block/bio.c:bio_free
```
```
In block/blk-cgroup.c (ffffffff814f1976)
Location: include/linux/blk-cgroup.h:542
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814f47da)
Location: include/linux/blk-cgroup.h:542
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff814de3b9)
Location: include/linux/blk-cgroup.h:544
Inline: True
```
```
In block/blk-cgroup.c (ffffffff8150b01b)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8150dd74)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff8153e217)
Location: include/linux/blk-cgroup.h:513
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-cgroup.c (ffffffff8156bfee)
Location: include/linux/blk-cgroup.h:513
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8156e30a)
Location: include/linux/blk-cgroup.h:513
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff8155a537)
Location: include/linux/blk-cgroup.h:477
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-cgroup.c (ffffffff81585a54)
Location: include/linux/blk-cgroup.h:477
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81589857)
Location: include/linux/blk-cgroup.h:477
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff81562d17)
Location: include/linux/blk-cgroup.h:477
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-cgroup.c (ffffffff8158c424)
Location: include/linux/blk-cgroup.h:477
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81590257)
Location: include/linux/blk-cgroup.h:477
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff815c6987)
Location: include/linux/blk-cgroup.h:482
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-cgroup.c (ffffffff815f1a54)
Location: include/linux/blk-cgroup.h:482
Inline: True
Inline callers:
  - block/blk-cgroup.c:bio_clone_blkg_association
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff815f7062)
Location: include/linux/blk-cgroup.h:482
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff81671848)
Location: block/blk-cgroup.h:357
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-cgroup.c (ffffffff816a4b2b)
Location: block/blk-cgroup.h:357
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff816a877e)
Location: block/blk-cgroup.h:357
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff8172d0b8)
Location: block/blk-cgroup.h:341
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-cgroup.c (ffffffff817638bb)
Location: block/blk-cgroup.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8176718e)
Location: block/blk-cgroup.h:341
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff81769458)
Location: block/blk-cgroup.h:342
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-cgroup.c (ffffffff817a2956)
Location: block/blk-cgroup.h:342
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_free_workfn
```
```
In block/blk-throttle.c (ffffffff817a6253)
Location: block/blk-cgroup.h:342
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff817ab4d8)
Location: block/blk-cgroup.h:341
Inline: True
Inline callers:
  - block/bio.c:bio_uninit
```
```
In block/blk-cgroup.c (ffffffff817e6499)
Location: block/blk-cgroup.h:341
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkcg_activate_policy
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:blkg_free_workfn
```
```
In block/blk-throttle.c (ffffffff817e9f93)
Location: block/blk-cgroup.h:341
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffff8000105db5a0)
Location: include/linux/blk-cgroup.h:544
Inline: True
```
```
In block/blk-cgroup.c (ffff80001060e8a8)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffff8000106119d4)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (c078831c)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/bio.c:__bio_associate_blkg
```
```
In block/blk-cgroup.c (c07b91c4)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c07bc144)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (c00000000076b64c)
Location: include/linux/blk-cgroup.h:544
Inline: True
```
```
In block/blk-cgroup.c (c0000000007abe10)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (c0000000007afa04)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffe00041e3f0)
Location: include/linux/blk-cgroup.h:544
Inline: True
```
```
In block/blk-cgroup.c (ffffffe000446d36)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffe0004492a4)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff814d6999)
Location: include/linux/blk-cgroup.h:544
Inline: True
```
```
In block/blk-cgroup.c (ffffffff815035fb)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff81506354)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff814c7359)
Location: include/linux/blk-cgroup.h:544
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814f3abb)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff814f6814)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff814d2a29)
Location: include/linux/blk-cgroup.h:544
Inline: True
```
```
In block/blk-cgroup.c (ffffffff814ff68b)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff815023e4)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
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
In block/bio.c (ffffffff814eb549)
Location: include/linux/blk-cgroup.h:544
Inline: True
```
```
In block/blk-cgroup.c (ffffffff81518836)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_maybe_throttle_current
  - block/blk-cgroup.c:blkg_create
  - block/blk-cgroup.c:__blkg_release
```
```
In block/blk-throttle.c (ffffffff8151b724)
Location: include/linux/blk-cgroup.h:544
Inline: True
Inline callers:
  - block/blk-throttle.c:tg_dispatch_one_bio
  - block/blk-throttle.c:throtl_pop_queued
```
</details>
</li>
</ul>

## Differences
