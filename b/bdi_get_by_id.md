# Function: <code>bdi_get_by_id</code>

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
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81249460)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81249460-ffffffff812494d6: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277750)
Location: mm/backing-dev.c:915
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81277750-ffffffff812777e7: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81281e00)
Location: mm/backing-dev.c:785
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81281e00-ffffffff81281e97: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81286dc0)
Location: mm/backing-dev.c:784
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81286dc0-ffffffff81286e57: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812c6370)
Location: mm/backing-dev.c:858
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff812c6370-ffffffff812c6407: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81324360)
Location: mm/backing-dev.c:848
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81324360-ffffffff81324404: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81398c80)
Location: mm/backing-dev.c:971
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81398c80-ffffffff81398d24: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813cbbe0)
Location: mm/backing-dev.c:984
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff813cbbe0-ffffffff813cbc84: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff813f6550)
Location: mm/backing-dev.c:980
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff813f6550-ffffffff813f65f4: bdi_get_by_id (STB_GLOBAL)
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
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102deac8)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffff8000102deac8-ffff8000102debb8: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c0503afc)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
c0503afc-c0503b88: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039e3f0)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
c00000000039e3f0-c00000000039e4d8: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffe0001f6a1a)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffe0001f6a1a-ffffffe0001f6a94: bdi_get_by_id (STB_GLOBAL)
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
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81241ab0)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81241ab0-ffffffff81241b26: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81234aa0)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81234aa0-ffffffff81234b16: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123f850)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff8123f850-ffffffff8123f8c6: bdi_get_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct backing_dev_info *bdi_get_by_id(u64 id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124efd0)
Location: mm/backing-dev.c:917
Inline: False
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff8124efd0-ffffffff8124f046: bdi_get_by_id (STB_GLOBAL)
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
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
