# Function: <code>mm_unaccount_pinned_pages</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833d60)
Location: net/core/skbuff.c:923
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a690)
Location: net/core/skbuff.c:926
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff8187a690-ffffffff8187a6b4: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b270)
Location: net/core/skbuff.c:928
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff8189b270-ffffffff8189b294: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5af0)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff818e5af0-ffffffff818e5b14: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917c40)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff81917c40-ffffffff81917c64: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed628)
Location: net/core/skbuff.c:1085
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff819ea080-ffffffff819ea0a4: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed2e8)
Location: net/core/skbuff.c:1096
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff819e9db0-ffffffff819e9dd4: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d5575)
Location: net/core/skbuff.c:1139
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
**Symbols:**

```
ffffffff819d02f0-ffffffff819d0314: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a85231)
Location: net/core/skbuff.c:1160
Inline: True
Inline callers:
  - net/core/skbuff.c:msg_zerocopy_callback
```
**Symbols:**

```
ffffffff81a7fe50-ffffffff81a7fe74: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bfb255)
Location: net/core/skbuff.c:1162
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
**Symbols:**

```
ffffffff81bf4390-ffffffff81bf43c8: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da9f65)
Location: net/core/skbuff.c:1342
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
**Symbols:**

```
ffffffff81da21d0-ffffffff81da2208: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e18d05)
Location: net/core/skbuff.c:1486
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
**Symbols:**

```
ffffffff81e10aa0-ffffffff81e10ad8: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed6195)
Location: net/core/skbuff.c:1574
Inline: True
Inline callers:
  - net/core/skbuff.c:__msg_zerocopy_callback
```
**Symbols:**

```
ffffffff81ecd5c0-ffffffff81ecd5f8: mm_unaccount_pinned_pages (STB_GLOBAL)
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
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb3810)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffff800010bb3810-ffff800010bb3868: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce968)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
c0cce968-c0cce9b4: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87d50)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
c000000000c87d50-c000000000c87dac: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000745b76)
Location: net/core/skbuff.c:1086
Inline: True
Inline callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffe0007429e4-ffffffe000742a22: mm_unaccount_pinned_pages (STB_GLOBAL)
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
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7c40)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff818b7c40-ffffffff818b7c64: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871b90)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff81871b90-ffffffff81871bb4: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908c40)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff81908c40-ffffffff81908c64: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mm_unaccount_pinned_pages(struct mmpin *mmp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929cf0)
Location: net/core/skbuff.c:1086
Inline: False
Direct callers:
  - net/core/skbuff.c:sock_zerocopy_callback
```
**Symbols:**

```
ffffffff81929cf0-ffffffff81929d14: mm_unaccount_pinned_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
