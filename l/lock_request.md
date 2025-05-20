# Function: <code>lock_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int lock_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130d680)
Location: fs/fuse/dev.c:670
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8130d680-ffffffff8130d6cf: lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int lock_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81341990)
Location: fs/fuse/dev.c:645
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81341990-ffffffff813419df: lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int lock_request(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813577e0)
Location: fs/fuse/dev.c:649
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff813577e0-ffffffff8135782f: lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136d4d0)
Location: fs/fuse/dev.c:648
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff8136c840-ffffffff8136c886: lock_request.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81391f50)
Location: fs/fuse/dev.c:648
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
```
**Symbols:**

```
ffffffff81391410-ffffffff81391456: lock_request.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c0f79)
Location: fs/fuse/dev.c:661
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff813c04f0-ffffffff813c0536: lock_request.part.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff813da2db)
Location: fs/fuse/dev.c:715
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_copy_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff813d9b40-ffffffff813d9b86: lock_request.part.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8140600a)
Location: fs/fuse/dev.c:739
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff81405720-ffffffff81405766: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81420a89)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff8141f680-ffffffff8141f6c3: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146f9bf)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/fuse/dev.c (ffffffff8148a206)
Location: fs/fuse/dev.c:618
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/fuse/dev.c (ffffffff8148fd56)
Location: fs/fuse/dev.c:618
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/fuse/dev.c (ffffffff814e77c6)
Location: fs/fuse/dev.c:618
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_copy_fill
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
In fs/fuse/dev.c (ffffffff81575b29)
Location: fs/fuse/dev.c:610
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
  - fs/fuse/dev.c:fuse_copy_fill
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161ae86)
Location: fs/fuse/dev.c:610
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff81619900-ffffffff8161994b: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81652ff6)
Location: fs/fuse/dev.c:612
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff81651ab0-ffffffff81651afb: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168c606)
Location: fs/fuse/dev.c:612
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff8168b0c0-ffffffff8168b10b: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffff800010503794)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffff800010501da0-ffff800010501e8c: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (c06bfe3c)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
c06beee4-c06bef48: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (c00000000064806c)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
c0000000006479a0-c000000000647a7c: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffe000370598)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffe00036efcc-ffffffe00036f052: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81419069)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff81417c60-ffffffff81417ca3: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81409ae9)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff814086e0-ffffffff81408723: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff81415209)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff81413e00-ffffffff81413e43: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142bf77)
Location: fs/fuse/dev.c:605
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
Direct callers:
  - fs/fuse/dev.c:fuse_try_move_page
  - fs/fuse/dev.c:fuse_copy_fill
```
**Symbols:**

```
ffffffff8142ae40-ffffffff8142ae85: lock_request.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
