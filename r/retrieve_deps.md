# Function: <code>retrieve_deps</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff816aa3df)
Location: drivers/md/dm-ioctl.c:1393
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8170a84f)
Location: drivers/md/dm-ioctl.c:1403
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8173c71f)
Location: drivers/md/dm-ioctl.c:1403
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81756102)
Location: drivers/md/dm-ioctl.c:1421
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff817c8312)
Location: drivers/md/dm-ioctl.c:1428
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81810db3)
Location: drivers/md/dm-ioctl.c:1429
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8183cdb3)
Location: drivers/md/dm-ioctl.c:1429
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffffffff8187fca1)
Location: drivers/md/dm-ioctl.c:1429
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffffffff818b1b61)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void retrieve_deps(struct dm_table *table, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81980a20)
Location: drivers/md/dm-ioctl.c:1454
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81980a20-ffffffff81980b22: retrieve_deps (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void retrieve_deps(struct dm_table *table, struct dm_ioctl *param, size_t param_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff81985040)
Location: drivers/md/dm-ioctl.c:1454
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_deps
```
**Symbols:**

```
ffffffff81985040-ffffffff81985143: retrieve_deps (STB_LOCAL)
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
In drivers/md/dm-ioctl.c (ffffffff8196af3b)
Location: drivers/md/dm-ioctl.c:1531
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffffffff81a133fb)
Location: drivers/md/dm-ioctl.c:1546
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffffffff81b7bca2)
Location: drivers/md/dm-ioctl.c:1553
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffffffff81d191b2)
Location: drivers/md/dm-ioctl.c:1560
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffffffff81d824ab)
Location: drivers/md/dm-ioctl.c:1624
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffffffff81e39b1f)
Location: drivers/md/dm-ioctl.c:1624
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffff800010b08984)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c0be66e0)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (c000000000bfa414)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffe0006f72f6)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
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
In drivers/md/dm-ioctl.c (ffffffff818579e1)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff8181eff1)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ioctl.c (ffffffff818a7011)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
In drivers/md/dm-ioctl.c (ffffffff818c3251)
Location: drivers/md/dm-ioctl.c:1454
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:table_deps
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
