# Function: <code>dax_recovery_write</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t dax_recovery_write(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff819e8d40)
Location: drivers/dax/super.c:198
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
  - drivers/md/dm-linear.c:linear_dax_recovery_write
  - drivers/md/dm-stripe.c:stripe_dax_recovery_write
```
**Symbols:**

```
ffffffff819e8d40-ffffffff819e8d81: dax_recovery_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t dax_recovery_write(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81b65110)
Location: drivers/dax/super.c:220
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
  - drivers/md/dm-linear.c:linear_dax_recovery_write
  - drivers/md/dm-stripe.c:stripe_dax_recovery_write
```
**Symbols:**

```
ffffffff81b65110-ffffffff81b65151: dax_recovery_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t dax_recovery_write(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81bb8710)
Location: drivers/dax/super.c:223
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
  - drivers/md/dm-linear.c:linear_dax_recovery_write
  - drivers/md/dm-stripe.c:stripe_dax_recovery_write
```
**Symbols:**

```
ffffffff81bb8710-ffffffff81bb8751: dax_recovery_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t dax_recovery_write(struct dax_device *dax_dev, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81c0cd70)
Location: drivers/dax/super.c:223
Inline: False
Direct callers:
  - fs/dax.c:dax_iomap_iter
  - drivers/md/dm-linear.c:linear_dax_recovery_write
  - drivers/md/dm-stripe.c:stripe_dax_recovery_write
```
**Symbols:**

```
ffffffff81c0cd70-ffffffff81c0cdb1: dax_recovery_write (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
