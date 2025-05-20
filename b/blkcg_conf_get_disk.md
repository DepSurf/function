# Function: <code>blkcg_conf_get_disk</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8150a930)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8150a930-ffffffff8150a9f5: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156b8a0)
Location: block/blk-cgroup.c:588
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff8156b8a0-ffffffff8156b965: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060df50)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffff80001060df50-ffff80001060e034: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b89b4)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
c07b89b4-c07b8aa0: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007ab260)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
c0000000007ab260-c0000000007ab390: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe00044657a)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffe00044657a-ffffffe00044664a: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81502f10)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81502f10-ffffffff81502fd5: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f33f0)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff814f33f0-ffffffff814f34b5: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814fefa0)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff814fefa0-ffffffff814ff065: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gendisk *blkcg_conf_get_disk(char **inputp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81518120)
Location: block/blk-cgroup.c:767
Inline: False
Direct callers:
  - block/blk-cgroup.c:blkg_conf_prep
  - block/blk-iocost.c:ioc_cost_model_write
  - block/blk-iocost.c:ioc_qos_write
```
**Symbols:**

```
ffffffff81518120-ffffffff815181e5: blkcg_conf_get_disk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
