# Function: <code>dm_message_test_buffer_overflow</code>

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
In drivers/md/dm-ioctl.c (ffffffff816a8c0b)
Location: drivers/md/dm.h:234
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff816ada39)
Location: drivers/md/dm.h:234
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
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
In drivers/md/dm-ioctl.c (ffffffff81709094)
Location: drivers/md/dm-core.h:144
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff8170df36)
Location: drivers/md/dm-core.h:144
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
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
In drivers/md/dm-ioctl.c (ffffffff8173af64)
Location: drivers/md/dm-core.h:144
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81740404)
Location: drivers/md/dm-core.h:144
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
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
In drivers/md/dm-ioctl.c (ffffffff817548a3)
Location: drivers/md/dm-core.h:145
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff8175a61b)
Location: drivers/md/dm-core.h:145
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
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
In drivers/md/dm-ioctl.c (ffffffff817c6a53)
Location: drivers/md/dm-core.h:146
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff817cc84e)
Location: drivers/md/dm-core.h:146
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
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
In drivers/md/dm-ioctl.c (ffffffff818101b7)
Location: drivers/md/dm-core.h:143
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81815224)
Location: drivers/md/dm-core.h:143
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
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
In drivers/md/dm-ioctl.c (ffffffff8183c1b7)
Location: drivers/md/dm-core.h:128
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81841234)
Location: drivers/md/dm-core.h:128
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
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
In drivers/md/dm-ioctl.c (ffffffff8187e377)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81883a28)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff818b0507)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff818b5948)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff8198075f)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81986678)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff81984d83)
Location: drivers/md/dm-core.h:178
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff8198a6ea)
Location: drivers/md/dm-core.h:178
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff8196a4c3)
Location: drivers/md/dm-core.h:183
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff8196ec9c)
Location: drivers/md/dm-core.h:183
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff81a12963)
Location: drivers/md/dm-core.h:253
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81a1758c)
Location: drivers/md/dm-core.h:253
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff81b7b184)
Location: drivers/md/dm-core.h:310
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81b80318)
Location: drivers/md/dm-core.h:310
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff81d177b6)
Location: drivers/md/dm-core.h:331
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81d1da48)
Location: drivers/md/dm-core.h:331
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff81d80a46)
Location: drivers/md/dm-core.h:332
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81d86c3b)
Location: drivers/md/dm-core.h:332
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff81e380a6)
Location: drivers/md/dm-core.h:335
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81e3e34b)
Location: drivers/md/dm-core.h:335
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffff800010b0761c)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffff800010b0d790)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (c0be6108)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (c0beb8f0)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (c000000000bf85bc)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (c000000000c002c8)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffe0006f5e9e)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffe0006fb65a)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_message
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
In drivers/md/dm-ioctl.c (ffffffff81856387)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff8185b7c8)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff8181d997)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff81822d98)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff818a59b7)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff818aadf8)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
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
In drivers/md/dm-ioctl.c (ffffffff818c1bf7)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:target_message
```
```
In drivers/md/dm-stats.c (ffffffff818c6a28)
Location: drivers/md/dm-core.h:129
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_create
```
</details>
</li>
</ul>

## Differences
