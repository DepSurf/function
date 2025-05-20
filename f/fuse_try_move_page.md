# Function: <code>fuse_try_move_page</code>

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
In fs/fuse/dev.c (ffffffff8130e83a)
Location: fs/fuse/dev.c:848
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/fuse/dev.c (ffffffff81342ba7)
Location: fs/fuse/dev.c:823
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/fuse/dev.c (ffffffff813589de)
Location: fs/fuse/dev.c:826
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/fuse/dev.c (ffffffff8136d1e3)
Location: fs/fuse/dev.c:825
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/fuse/dev.c (ffffffff81391d9e)
Location: fs/fuse/dev.c:825
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/fuse/dev.c (ffffffff813c0df3)
Location: fs/fuse/dev.c:838
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
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
In fs/fuse/dev.c (ffffffff813da153)
Location: fs/fuse/dev.c:892
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:916
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81405d80-ffffffff8140612e: fuse_try_move_page (STB_LOCAL)
ffffffff81409416-ffffffff81409503: fuse_try_move_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff814208e0-ffffffff81420c8d: fuse_try_move_page (STB_LOCAL)
ffffffff81422ec3-ffffffff81422f45: fuse_try_move_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146f8f0)
Location: fs/fuse/dev.c:781
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8146f8f0-ffffffff8146fcf5: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148a120)
Location: fs/fuse/dev.c:794
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8148a120-ffffffff8148a592: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148fc70)
Location: fs/fuse/dev.c:795
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8148fc70-ffffffff8149006e: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e76e0)
Location: fs/fuse/dev.c:795
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff814e76e0-ffffffff814e7af4: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81575a30)
Location: fs/fuse/dev.c:787
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81575a30-ffffffff8157607a: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161add0)
Location: fs/fuse/dev.c:787
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8161add0-ffffffff8161b16e: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81652f40)
Location: fs/fuse/dev.c:789
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81652f40-ffffffff816532df: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168c550)
Location: fs/fuse/dev.c:789
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8168c550-ffffffff8168c8e2: fuse_try_move_page (STB_LOCAL)
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
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff8000105034c0)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffff8000105034c0-ffff800010503940: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06bfb50)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
c06bfb50-c06bffd8: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000647f90)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
c000000000647f90-c0000000006485d0: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe000370332)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffe000370332-ffffffe0003706e4: fuse_try_move_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81418ec0-ffffffff8141926d: fuse_try_move_page (STB_LOCAL)
ffffffff8141b4a3-ffffffff8141b525: fuse_try_move_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81409940-ffffffff81409ced: fuse_try_move_page (STB_LOCAL)
ffffffff8140bf23-ffffffff8140bfa5: fuse_try_move_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81415060-ffffffff8141540d: fuse_try_move_page (STB_LOCAL)
ffffffff81417643-ffffffff814176c5: fuse_try_move_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fuse_try_move_page(struct fuse_copy_state *cs, struct page **pagep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:782
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8142bde0-ffffffff8142c176: fuse_try_move_page (STB_LOCAL)
ffffffff8142e3d3-ffffffff8142e43d: fuse_try_move_page.cold (STB_LOCAL)
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
