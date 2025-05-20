# Function: <code>mddev_destroy_wb_pool</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81861b60)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
ffffffff81861b60-ffffffff81861bf5: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81893790)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
ffffffff81893790-ffffffff81893825: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010aea3e0)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
ffff800010aea3e0-ffff800010aea4d8: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bc9150)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
c0bc9150-c0bc9200: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd1310)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
c000000000bd1310-c000000000bd1418: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006dc058)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
ffffffe0006dc058-ffffffe0006dc0f0: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81839610)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
ffffffff81839610-ffffffff818396a5: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81800c80)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
ffffffff81800c80-ffffffff81800d15: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81888c40)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
ffffffff81888c40-ffffffff81888cd5: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mddev_destroy_wb_pool(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff818a6370)
Location: drivers/md/md.c:174
Inline: True
Direct callers:
  - drivers/md/md.c:state_store
  - drivers/md/md.c:unbind_rdev_from_array
```
**Symbols:**

```
ffffffff818a6370-ffffffff818a6405: mddev_destroy_wb_pool (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
