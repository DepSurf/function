# Function: <code>bdi_register_owner</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c7aa0)
Location: mm/backing-dev.c:828
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff811c7aa0-ffffffff811c7af4: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d7bc0)
Location: mm/backing-dev.c:834
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff811d7bc0-ffffffff811d7c14: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811e0dd0)
Location: mm/backing-dev.c:897
Inline: True
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff811e0dd0-ffffffff811e0e31: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811f6de0)
Location: mm/backing-dev.c:912
Inline: True
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff811f6de0-ffffffff811f6e41: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81218070)
Location: mm/backing-dev.c:910
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81218070-ffffffff812180d1: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8122aeb0)
Location: mm/backing-dev.c:913
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8122aeb0-ffffffff8122af11: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/backing-dev.c (ffffffff8123abf8)
Location: mm/backing-dev.c:900
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8123bd8c-ffffffff8123bd9f: bdi_register_owner.cold (STB_LOCAL)
ffffffff8123abc0-ffffffff8123ac1f: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81248f60)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81248f60-ffffffff81248fbf: bdi_register_owner (STB_GLOBAL)
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
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102de358)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffff8000102de358-ffff8000102de3cc: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c050353c)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
c050353c-c05035b4: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039ddc0)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
c00000000039ddc0-c00000000039de50: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f65d8)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffe0001f65d8-ffffffe0001f6640: bdi_register_owner (STB_GLOBAL)
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
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812415b0)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff812415b0-ffffffff8124160f: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812345b0)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff812345b0-ffffffff8123460f: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123f350)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8123f350-ffffffff8123f3af: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bdi_register_owner(struct backing_dev_info *bdi, struct device *owner);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124ea90)
Location: mm/backing-dev.c:980
Inline: True
Direct callers:
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff8124ea90-ffffffff8124eaef: bdi_register_owner (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
