# Function: <code>rdev_need_serial</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81969353)
Location: drivers/md/md.c:199
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8196fe63)
Location: drivers/md/md.c:197
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
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
In drivers/md/md.c (ffffffff81953da3)
Location: drivers/md/md.c:197
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
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
In drivers/md/md.c (ffffffff819f9373)
Location: drivers/md/md.c:198
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
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
In drivers/md/md.c (ffffffff81b60813)
Location: drivers/md/md.c:199
Inline: True
Inline callers:
  - drivers/md/md.c:mddev_create_serial_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int rdev_need_serial(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf4660)
Location: drivers/md/md.c:211
Inline: True
Direct callers:
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81cf4660-ffffffff81cf46ab: rdev_need_serial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int rdev_need_serial(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d5c4a0)
Location: drivers/md/md.c:197
Inline: True
Direct callers:
  - drivers/md/md.c:mddev_destroy_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81d5c4a0-ffffffff81d5c4e8: rdev_need_serial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int rdev_need_serial(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e13630)
Location: drivers/md/md.c:217
Inline: True
Direct callers:
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81e13630-ffffffff81e13678: rdev_need_serial (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
