# Function: <code>blkcg_bio_issue_init</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498272)
Location: include/linux/blk-cgroup.h:767
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8149d61c)
Location: include/linux/blk-cgroup.h:767
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814be42f)
Location: include/linux/blk-cgroup.h:767
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
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
In block/bio.c (ffffffff814c60ef)
Location: include/linux/blk-cgroup.h:719
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cb855)
Location: include/linux/blk-cgroup.h:719
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814ecbb7)
Location: include/linux/blk-cgroup.h:719
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff814de4f2)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814e4b18)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff81506007)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff8153e011)
Location: include/linux/blk-cgroup.h:568
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff81542b9a)
Location: include/linux/blk-cgroup.h:568
Inline: True
Inline callers:
  - block/blk-core.c:blkcg_bio_issue_check
```
```
In block/bounce.c (ffffffff81566830)
Location: include/linux/blk-cgroup.h:568
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff81582903)
Location: include/linux/blk-cgroup.h:568
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/bio.c (ffffffff8155a000)
Location: include/linux/blk-cgroup.h:524
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8156015f)
Location: include/linux/blk-cgroup.h:524
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/bounce.c (ffffffff81581736)
Location: include/linux/blk-cgroup.h:524
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff8159f7eb)
Location: include/linux/blk-cgroup.h:524
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/bio.c (ffffffff81562921)
Location: include/linux/blk-cgroup.h:524
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff815682ed)
Location: include/linux/blk-cgroup.h:524
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-crypto-fallback.c (ffffffff815a6509)
Location: include/linux/blk-cgroup.h:524
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/bio.c (ffffffff815c6641)
Location: include/linux/blk-cgroup.h:529
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff815cc8f6)
Location: include/linux/blk-cgroup.h:529
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
```
```
In block/blk-crypto-fallback.c (ffffffff8160f029)
Location: include/linux/blk-cgroup.h:529
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
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
In block/blk-core.c (ffffffff816794d7)
Location: block/blk-cgroup.h:404
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff8168049b)
Location: block/blk-cgroup.h:404
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
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
In block/blk-core.c (ffffffff81735628)
Location: block/blk-cgroup.h:388
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff8173d8ba)
Location: block/blk-cgroup.h:388
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
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
In block/blk-core.c (ffffffff81771bc8)
Location: block/blk-cgroup.h:379
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff81779e37)
Location: block/blk-cgroup.h:379
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
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
In block/blk-core.c (ffffffff817b3f08)
Location: block/blk-cgroup.h:378
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-merge.c (ffffffff817bc217)
Location: block/blk-cgroup.h:378
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
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
In block/bio.c (ffff8000105db94c)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffff8000105e2e44)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/bio.c (c07884f4)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c078f1d0)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (c07b331c)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (c00000000076b890)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c000000000775430)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/bio.c (ffffffe00041e56e)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffe00042410a)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
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
In block/bio.c (ffffffff814d6ad2)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814dd0f8)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814fe5e7)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff814c7492)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cdaa3)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814eeaf7)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff814d2b62)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814d9188)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff814fa677)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bio.c (ffffffff814eb6f2)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814f1da7)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
```
```
In block/bounce.c (ffffffff81513802)
Location: include/linux/blk-cgroup.h:721
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
</ul>

## Differences
