# Function: <code>blkcg_destroy_blkgs</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814c2fd0)
Location: block/blk-cgroup.c:1085
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff814c2fd0-ffffffff814c3071: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f1620)
Location: block/blk-cgroup.c:1050
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff814f1620-ffffffff814f16bf: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8150ac10)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff8150ac10-ffffffff8150acac: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8156bc60)
Location: block/blk-cgroup.c:901
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff8156bc60-ffffffff8156bcfc: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff81586930)
Location: block/blk-cgroup.c:1017
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff81586930-ffffffff815869f7: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff8158d640)
Location: block/blk-cgroup.c:1022
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff8158d640-ffffffff8158d707: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815f30c0)
Location: block/blk-cgroup.c:1030
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff815f30c0-ffffffff815f3187: blkcg_destroy_blkgs (STB_GLOBAL)
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
In block/blk-cgroup.c (ffffffff816a4655)
Location: block/blk-cgroup.c:1074
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
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
In block/blk-cgroup.c (ffffffff81763385)
Location: block/blk-cgroup.c:1086
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
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
In block/blk-cgroup.c (ffffffff817a24d5)
Location: block/blk-cgroup.c:1219
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
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
In block/blk-cgroup.c (ffffffff817e6015)
Location: block/blk-cgroup.c:1232
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_unpin_online
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffff80001060e350)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffff80001060e350-ffff80001060e4c4: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c07b8ccc)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
c07b8ccc-c07b8db8: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (c0000000007ab790)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
c0000000007ab790-c0000000007ab930: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffe00044689e)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffe00044689e-ffffffe0004469de: blkcg_destroy_blkgs (STB_GLOBAL)
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
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815031f0)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff815031f0-ffffffff8150328c: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814f36d0)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff814f36d0-ffffffff814f3760: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff814ff280)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff814ff280-ffffffff814ff31c: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blkcg_destroy_blkgs(struct blkcg *blkcg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-cgroup.c (ffffffff815183f0)
Location: block/blk-cgroup.c:1079
Inline: False
Direct callers:
  - mm/backing-dev.c:cgwb_release_workfn
  - block/blk-cgroup.c:blkcg_css_offline
```
**Symbols:**

```
ffffffff815183f0-ffffffff8151847b: blkcg_destroy_blkgs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
