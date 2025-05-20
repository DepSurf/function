# Function: <code>rdev_read_only</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8194d915)
Location: drivers/md/md.c:2379
Inline: True
Inline callers:
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
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
In drivers/md/md.c (ffffffff819f2d25)
Location: drivers/md/md.c:2389
Inline: True
Inline callers:
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool rdev_read_only(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2383
Inline: False
Direct callers:
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81b5c3d0-ffffffff81b5c486: rdev_read_only (STB_LOCAL)
ffffffff81ef3717-ffffffff81ef376a: rdev_read_only.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool rdev_read_only(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2374
Inline: False
Direct callers:
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81cf6860-ffffffff81cf691c: rdev_read_only (STB_LOCAL)
ffffffff820a7e39-ffffffff820a7e8c: rdev_read_only.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rdev_read_only(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2350
Inline: False
Direct callers:
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81d5e300-ffffffff81d5e3b6: rdev_read_only (STB_LOCAL)
ffffffff82129217-ffffffff8212926a: rdev_read_only.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rdev_read_only(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:2480
Inline: False
Direct callers:
  - drivers/md/md.c:restart_array
  - drivers/md/md.c:md_run
  - drivers/md/md.c:bind_rdev_to_array
```
**Symbols:**

```
ffffffff81e15160-ffffffff81e15216: rdev_read_only (STB_LOCAL)
ffffffff8220ac00-ffffffff8220ac53: rdev_read_only.cold (STB_LOCAL)
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
