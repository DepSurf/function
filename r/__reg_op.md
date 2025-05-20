# Function: <code>__reg_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff813f9190)
Location: lib/bitmap.c:946
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
```
**Symbols:**

```
ffffffff813f9190-ffffffff813f924e: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81440070)
Location: lib/bitmap.c:948
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff81440070-ffffffff8144012e: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8145d170)
Location: lib/bitmap.c:990
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff8145d170-ffffffff8145d22e: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81462565)
Location: lib/bitmap.c:996
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff81462400-ffffffff814624b3: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8148e445)
Location: lib/bitmap.c:992
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff8148e2e0-ffffffff8148e393: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814c30cf)
Location: lib/bitmap.c:989
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
```
**Symbols:**

```
ffffffff814c2ff0-ffffffff814c309c: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff814d777f)
Location: lib/bitmap.c:984
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
```
**Symbols:**

```
ffffffff814d76a0-ffffffff814d774c: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8150364d)
Location: lib/bitmap.c:1012
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff815034e0-ffffffff81503588: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff815215ed)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff81521480-ffffffff81521528: __reg_op (STB_LOCAL)
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
In lib/bitmap.c (ffffffff81584e80)
Location: lib/bitmap.c:1107
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
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
In lib/bitmap.c (ffffffff815a1f83)
Location: lib/bitmap.c:1107
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
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
In lib/bitmap.c (ffffffff815a8e93)
Location: lib/bitmap.c:1118
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (0)
Location: lib/bitmap.c:1249
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff81611700-ffffffff816117f1: __reg_op (STB_LOCAL)
ffffffff81cda75e-ffffffff81cda796: __reg_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (0)
Location: lib/bitmap.c:1266
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff816dd890-ffffffff816dd9bb: __reg_op (STB_LOCAL)
ffffffff81e92da3-ffffffff81e92ddb: __reg_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (0)
Location: lib/bitmap.c:1247
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff817cd7e0-ffffffff817cd90b: __reg_op (STB_LOCAL)
ffffffff82077f86-ffffffff82077fbe: __reg_op.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/bitmap.c (0)
Location: lib/bitmap.c:1247
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff8180bbf0-ffffffff8180bd84: __reg_op (STB_LOCAL)
ffffffff820f82b6-ffffffff820f82ef: __reg_op.cold (STB_LOCAL)
```
</details>
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
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffff80001062ad18)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffff80001062ab78-ffff80001062ac58: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c07d1f4c)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
c07d1da8-c07d1e94: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (c0000000007ccfcc)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
c0000000007cccf0-c0000000007cce78: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffe00045b60e)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffe00045b4a0-ffffffe00045b556: __reg_op (STB_LOCAL)
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
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81519bcd)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff81519a60-ffffffff81519b08: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81509ebd)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff81509d50-ffffffff81509df8: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff81515c5d)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff81515af0-ffffffff81515b98: __reg_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __reg_op(long unsigned int *bitmap, unsigned int pos, int order, int reg_op);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bitmap.c (ffffffff8152f3ed)
Location: lib/bitmap.c:1032
Inline: True
Inline callers:
  - lib/bitmap.c:bitmap_allocate_region
Direct callers:
  - lib/bitmap.c:bitmap_allocate_region
  - lib/bitmap.c:bitmap_release_region
  - lib/bitmap.c:bitmap_find_free_region
  - lib/bitmap.c:bitmap_find_free_region
```
**Symbols:**

```
ffffffff8152f280-ffffffff8152f328: __reg_op (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
