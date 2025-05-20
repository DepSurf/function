# Function: <code>overlaps</code>

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
In drivers/md/md.c (ffffffff81692616)
Location: drivers/md/md.c:2920
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff8122e6f2)
Location: mm/usercopy.c:79
Inline: True
```
```
In drivers/md/md.c (ffffffff816f30ab)
Location: drivers/md/md.c:2928
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff81240c1d)
Location: mm/usercopy.c:79
Inline: True
```
```
In drivers/md/md.c (ffffffff817247ab)
Location: drivers/md/md.c:2973
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff8124c91b)
Location: mm/usercopy.c:76
Inline: True
```
```
In drivers/md/md.c (ffffffff8173d8f6)
Location: drivers/md/md.c:3035
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff8126cddb)
Location: mm/usercopy.c:76
Inline: True
```
```
In drivers/md/md.c (ffffffff817af4ec)
Location: drivers/md/md.c:3090
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffff81291a1c)
Location: mm/usercopy.c:104
Inline: True
```
```
In drivers/md/md.c (ffffffff817f7c16)
Location: drivers/md/md.c:3106
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107f8d8)
Location: arch/x86/mm/pageattr.c:378
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
```
```
In mm/usercopy.c (ffffffff812a6a4a)
Location: mm/usercopy.c:106
Inline: True
```
```
In drivers/md/md.c (ffffffff81823ed6)
Location: drivers/md/md.c:3097
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810832cc)
Location: arch/x86/mm/pageattr.c:379
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
```
```
In mm/usercopy.c (ffffffff812c2124)
Location: mm/usercopy.c:102
Inline: True
```
```
In drivers/md/md.c (ffffffff81866376)
Location: drivers/md/md.c:3164
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8108439c)
Location: arch/x86/mm/pageattr.c:379
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
```
```
In mm/usercopy.c (ffffffff812d4054)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff818980b6)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dddf)
Location: arch/x86/mm/pat/set_memory.c:388
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In mm/usercopy.c (ffffffff81309db1)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff81966bca)
Location: drivers/md/md.c:3343
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dcaf)
Location: arch/x86/mm/pat/set_memory.c:388
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In mm/usercopy.c (ffffffff81315bd1)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff8196d762)
Location: drivers/md/md.c:3364
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e896)
Location: arch/x86/mm/pat/set_memory.c:396
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In mm/usercopy.c (ffffffff8131bdc1)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff81951942)
Location: drivers/md/md.c:3328
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e37a)
Location: arch/x86/mm/pat/set_memory.c:396
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In mm/usercopy.c (ffffffff813690a1)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff819f6ea9)
Location: drivers/md/md.c:3347
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810b1cdf)
Location: arch/x86/mm/pat/set_memory.c:399
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In mm/usercopy.c (ffffffff813e6e33)
Location: mm/usercopy.c:105
Inline: True
```
```
In drivers/md/md.c (ffffffff81b5f0e7)
Location: drivers/md/md.c:3338
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc45c)
Location: arch/x86/mm/pat/set_memory.c:434
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In mm/usercopy.c (ffffffff8146e9f9)
Location: mm/usercopy.c:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810cfa7b)
Location: arch/x86/mm/pat/set_memory.c:435
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In mm/usercopy.c (ffffffff814a31b9)
Location: mm/usercopy.c:106
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff810d815b)
Location: arch/x86/mm/pat/set_memory.c:435
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In mm/usercopy.c (ffffffff814d4059)
Location: mm/usercopy.c:106
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffff800010379fec)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffff800010ae76c8)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (c0565224)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (c0bcdef4)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (c00000000046d4c0)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (c000000000bd248c)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/usercopy.c (ffffffe0002512bc)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffe0006e01e2)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8108339c)
Location: arch/x86/mm/pageattr.c:379
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
```
```
In mm/usercopy.c (ffffffff812cc634)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff8183df36)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071e16)
Location: arch/x86/mm/pageattr.c:379
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
```
```
In mm/usercopy.c (ffffffff812bd4a4)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff81805596)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8108334c)
Location: arch/x86/mm/pageattr.c:379
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
```
```
In mm/usercopy.c (ffffffff812ca444)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff8188d566)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810855a2)
Location: arch/x86/mm/pageattr.c:379
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:__split_large_page
  - arch/x86/mm/pageattr.c:protect_kernel_text_ro
```
```
In mm/usercopy.c (ffffffff812db144)
Location: mm/usercopy.c:103
Inline: True
```
```
In drivers/md/md.c (ffffffff818a7022)
Location: drivers/md/md.c:3218
Inline: True
Inline callers:
  - drivers/md/md.c:rdev_size_store
```
</details>
</li>
</ul>

## Differences
