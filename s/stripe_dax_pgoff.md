# Function: <code>stripe_dax_pgoff</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff81b78990)
Location: drivers/md/dm-stripe.c:302
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_dax_recovery_write
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81b78990-ffffffff81b78a31: stripe_dax_pgoff.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff81d15fe0)
Location: drivers/md/dm-stripe.c:302
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_dax_recovery_write
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81d15fe0-ffffffff81d16081: stripe_dax_pgoff.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff81d7f240)
Location: drivers/md/dm-stripe.c:301
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_dax_recovery_write
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81d7f240-ffffffff81d7f2d9: stripe_dax_pgoff.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stripe.c (ffffffff81e36860)
Location: drivers/md/dm-stripe.c:301
Inline: True
Direct callers:
  - drivers/md/dm-stripe.c:stripe_dax_recovery_write
  - drivers/md/dm-stripe.c:stripe_dax_zero_page_range
  - drivers/md/dm-stripe.c:stripe_dax_direct_access
```
**Symbols:**

```
ffffffff81e36860-ffffffff81e368f9: stripe_dax_pgoff.isra.0 (STB_LOCAL)
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
