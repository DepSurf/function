# Function: <code>linear_dax_recovery_write</code>

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
size_t linear_dax_recovery_write(struct dm_target *ti, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81b77ff0)
Location: drivers/md/dm-linear.c:184
Inline: False
```
**Symbols:**

```
ffffffff81b77ff0-ffffffff81b78033: linear_dax_recovery_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t linear_dax_recovery_write(struct dm_target *ti, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81d155a0)
Location: drivers/md/dm-linear.c:184
Inline: False
```
**Symbols:**

```
ffffffff81d155a0-ffffffff81d155e3: linear_dax_recovery_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t linear_dax_recovery_write(struct dm_target *ti, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81d7e6f0)
Location: drivers/md/dm-linear.c:185
Inline: False
```
**Symbols:**

```
ffffffff81d7e6f0-ffffffff81d7e733: linear_dax_recovery_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t linear_dax_recovery_write(struct dm_target *ti, long unsigned int pgoff, void *addr, size_t bytes, struct iov_iter *i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-linear.c (ffffffff81e35d10)
Location: drivers/md/dm-linear.c:185
Inline: False
```
**Symbols:**

```
ffffffff81e35d10-ffffffff81e35d53: linear_dax_recovery_write (STB_LOCAL)
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
