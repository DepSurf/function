# Function: <code>purge_persistent_grants</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816d03b8)
Location: drivers/block/xen-blkfront.c:2652
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff8170be98)
Location: drivers/block/xen-blkfront.c:2652
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff81730198)
Location: drivers/block/xen-blkfront.c:2652
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void purge_persistent_grants(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817ebf40)
Location: drivers/block/xen-blkfront.c:2658
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
**Symbols:**

```
ffffffff817ebf40-ffffffff817ec088: purge_persistent_grants (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void purge_persistent_grants(struct blkfront_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81800870)
Location: drivers/block/xen-blkfront.c:2653
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
```
**Symbols:**

```
ffffffff81800870-ffffffff818009b8: purge_persistent_grants (STB_LOCAL)
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
In drivers/block/xen-blkfront.c (ffffffff817e6d1b)
Location: drivers/block/xen-blkfront.c:2653
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff818730ab)
Location: drivers/block/xen-blkfront.c:2526
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff819bb2ca)
Location: drivers/block/xen-blkfront.c:2521
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff81b307fa)
Location: drivers/block/xen-blkfront.c:2523
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff81b83cea)
Location: drivers/block/xen-blkfront.c:2524
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff81bd7c1a)
Location: drivers/block/xen-blkfront.c:2524
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffff80001092978c)
Location: drivers/block/xen-blkfront.c:2652
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff816f6cd8)
Location: drivers/block/xen-blkfront.c:2798
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff81723658)
Location: drivers/block/xen-blkfront.c:2652
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
In drivers/block/xen-blkfront.c (ffffffff8173eac8)
Location: drivers/block/xen-blkfront.c:2652
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_delay_work
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
