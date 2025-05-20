# Function: <code>to_bytes</code>

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
In drivers/md/dm.c (0)
Location: include/linux/device-mapper.h:599
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/device-mapper.h:599
Inline: True
```
```
In drivers/md/dm-io.c (0)
Location: include/linux/device-mapper.h:599
Inline: True
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
In drivers/md/dm.c (ffffffff817032cf)
Location: include/linux/device-mapper.h:634
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8170828f)
Location: include/linux/device-mapper.h:634
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff8170b49b)
Location: include/linux/device-mapper.h:634
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff8173519c)
Location: include/linux/device-mapper.h:635
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__split_and_process_bio
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8173a160)
Location: include/linux/device-mapper.h:635
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff8173d454)
Location: include/linux/device-mapper.h:635
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff8174d3d5)
Location: include/linux/device-mapper.h:641
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
```
In drivers/md/dm-stripe.c (ffffffff81753c44)
Location: include/linux/device-mapper.h:641
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81757205)
Location: include/linux/device-mapper.h:641
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff817bf5b5)
Location: include/linux/device-mapper.h:638
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__clone_and_map_simple_bio
```
```
In drivers/md/dm-stripe.c (ffffffff817c5df7)
Location: include/linux/device-mapper.h:638
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff817c944f)
Location: include/linux/device-mapper.h:638
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff81808780)
Location: include/linux/device-mapper.h:609
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff8180ebb5)
Location: include/linux/device-mapper.h:609
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81812182)
Location: include/linux/device-mapper.h:609
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff81834624)
Location: include/linux/device-mapper.h:617
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff8183ab86)
Location: include/linux/device-mapper.h:617
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff8183e0f8)
Location: include/linux/device-mapper.h:617
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff818763e9)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff8187d71e)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81880e26)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff818a81e8)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff818af4fe)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff818b2ce5)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff81978214)
Location: include/linux/device-mapper.h:623
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:clone_bio
  - drivers/md/dm.c:clone_bio
```
```
In drivers/md/dm-stripe.c (ffffffff8197f66b)
Location: include/linux/device-mapper.h:623
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map_range
```
```
In drivers/md/dm-io.c (ffffffff8198328f)
Location: include/linux/device-mapper.h:623
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In drivers/md/dm.c (ffffffff8197cefa)
Location: include/linux/device-mapper.h:635
Inline: True
Inline callers:
  - drivers/md/dm.c:__send_duplicate_bios
  - drivers/md/dm.c:clone_bio
  - drivers/md/dm.c:clone_bio
```
```
In drivers/md/dm-stripe.c (ffffffff81983a5e)
Location: include/linux/device-mapper.h:635
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map_range
```
```
In drivers/md/dm-io.c (ffffffff819873af)
Location: include/linux/device-mapper.h:635
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In drivers/md/dm.c (ffffffff81961216)
Location: include/linux/device-mapper.h:653
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff81967f42)
Location: include/linux/device-mapper.h:653
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff8196ba72)
Location: include/linux/device-mapper.h:653
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In drivers/md/dm.c (ffffffff81a0ae36)
Location: include/linux/device-mapper.h:663
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff81a10351)
Location: include/linux/device-mapper.h:663
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81a13f32)
Location: include/linux/device-mapper.h:663
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In drivers/md/dm.c (ffffffff81b7037a)
Location: include/linux/device-mapper.h:677
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-stripe.c (ffffffff81b78e33)
Location: include/linux/device-mapper.h:677
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81b7c6eb)
Location: include/linux/device-mapper.h:677
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In drivers/md/dm.c (ffffffff81d0cc8a)
Location: include/linux/device-mapper.h:676
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-stripe.c (ffffffff81d164d3)
Location: include/linux/device-mapper.h:676
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81d1a576)
Location: include/linux/device-mapper.h:676
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In drivers/md/dm.c (0)
Location: include/linux/device-mapper.h:716
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/device-mapper.h:716
Inline: True
```
```
In drivers/md/dm-io.c (ffffffff81d836d3)
Location: include/linux/device-mapper.h:716
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In drivers/md/dm.c (0)
Location: include/linux/device-mapper.h:717
Inline: True
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/device-mapper.h:717
Inline: True
```
```
In drivers/md/dm-io.c (ffffffff81e3adb3)
Location: include/linux/device-mapper.h:717
Inline: True
Inline callers:
  - drivers/md/dm-io.c:do_region
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
In drivers/md/dm.c (ffff800010afef50)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffff800010b0617c)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffff800010b0a3f0)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (c0bdddc8)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (c0be5298)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (c0be88ec)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (c000000000becdbc)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (c000000000bf6ca8)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (c000000000bfbf4c)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffe0006ee69a)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffe0006f4ffe)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffe0006f8410)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff8184e068)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff8185537e)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81858b65)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff81815688)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff8181c98e)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff81820175)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff8189d698)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff818a49ae)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff818a8195)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
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
In drivers/md/dm.c (ffffffff818b99f8)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__split_and_process_non_flush
  - drivers/md/dm.c:__send_duplicate_bios
```
```
In drivers/md/dm-stripe.c (ffffffff818c0bee)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
```
```
In drivers/md/dm-io.c (ffffffff818c43d5)
Location: include/linux/device-mapper.h:611
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dispatch_io
```
</details>
</li>
</ul>

## Differences
