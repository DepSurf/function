# Function: <code>ext4_groupinfo_create_slab</code>

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
In fs/ext4/mballoc.c (ffffffff812d339b)
Location: fs/ext4/mballoc.c:2536
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
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
In fs/ext4/mballoc.c (ffffffff81302aa9)
Location: fs/ext4/mballoc.c:2544
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81312e80)
Location: fs/ext4/mballoc.c:2544
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff81312e80-ffffffff81312f50: ext4_groupinfo_create_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8130a390)
Location: fs/ext4/mballoc.c:2558
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff8130a390-ffffffff8130a460: ext4_groupinfo_create_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8132ee70)
Location: fs/ext4/mballoc.c:2558
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff8132ee70-ffffffff8132ef40: ext4_groupinfo_create_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2527
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff8135d450-ffffffff8135d50e: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff81366069-ffffffff8136607f: ext4_groupinfo_create_slab.cold.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2527
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff81375980-ffffffff81375a3e: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff8137e4c9-ffffffff8137e4df: ext4_groupinfo_create_slab.cold.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2528
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff8139ef40-ffffffff8139effe: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff813a78cf-ffffffff813a78e5: ext4_groupinfo_create_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff813b7d60-ffffffff813b7e1e: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff813c076f-ffffffff813c0785: ext4_groupinfo_create_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2665
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff81403390-ffffffff81403430: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff8140c949-ffffffff8140c95f: ext4_groupinfo_create_slab.cold (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff8141cef2)
Location: fs/ext4/mballoc.c:2769
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
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
In fs/ext4/mballoc.c (ffffffff81423568)
Location: fs/ext4/mballoc.c:3272
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
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
In fs/ext4/mballoc.c (ffffffff81476de4)
Location: fs/ext4/mballoc.c:3292
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
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
In fs/ext4/mballoc.c (ffffffff814f90de)
Location: fs/ext4/mballoc.c:3289
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
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
In fs/ext4/mballoc.c (ffffffff8159383e)
Location: fs/ext4/mballoc.c:3239
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
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
In fs/ext4/mballoc.c (ffffffff815ca84e)
Location: fs/ext4/mballoc.c:3459
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
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
In fs/ext4/mballoc.c (ffffffff8160365e)
Location: fs/ext4/mballoc.c:3485
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
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
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff80001048dfe0)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffff80001048dfe0-ffff80001048e0d0: ext4_groupinfo_create_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c064ee08)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
c064ee08-c064eee8: ext4_groupinfo_create_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005b4c80)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
c0000000005b4c80-c0000000005b4dfc: ext4_groupinfo_create_slab (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe000313c46)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffe000313c46-ffffffe000313d80: ext4_groupinfo_create_slab (STB_LOCAL)
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
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff813b0340-ffffffff813b03fe: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff813b8d4f-ffffffff813b8d65: ext4_groupinfo_create_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff813a0dd0-ffffffff813a0e8e: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff813a97df-ffffffff813a97f5: ext4_groupinfo_create_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff813adba0-ffffffff813adc5e: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff813b65af-ffffffff813b65c5: ext4_groupinfo_create_slab.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ext4_groupinfo_create_slab(size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:2543
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff813c2560-ffffffff813c261e: ext4_groupinfo_create_slab (STB_LOCAL)
ffffffff813cb2ca-ffffffff813cb2e0: ext4_groupinfo_create_slab.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
