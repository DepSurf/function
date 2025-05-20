# Function: <code>bio_set_dev</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b703d9)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-linear.c (ffffffff81b77d8c)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81b78d07)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
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
In drivers/md/dm.c (ffffffff81d0cce9)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-linear.c (ffffffff81d152ec)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81d163a7)
Location: include/linux/bio.h:508
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
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
In drivers/md/dm.c (ffffffff81d75ab8)
Location: include/linux/bio.h:521
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-linear.c (ffffffff81d7e43c)
Location: include/linux/bio.h:521
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81d7f4c7)
Location: include/linux/bio.h:521
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
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
In drivers/md/dm.c (ffffffff81e2cbb8)
Location: include/linux/bio.h:536
Inline: True
Inline callers:
  - drivers/md/dm.c:alloc_tio
```
```
In drivers/md/dm-linear.c (ffffffff81e3590c)
Location: include/linux/bio.h:536
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_map
```
```
In drivers/md/dm-stripe.c (ffffffff81e36ae7)
Location: include/linux/bio.h:536
Inline: True
Inline callers:
  - drivers/md/dm-stripe.c:stripe_map
  - drivers/md/dm-stripe.c:stripe_map
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
