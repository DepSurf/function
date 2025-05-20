# Function: <code>md_bitmap_unplug</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8182eba0)
Location: drivers/md/md-bitmap.c:1008
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8182eba0-ffffffff8182ecaf: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818711b0)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff818711b0-ffffffff818712c4: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818a2fa0)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff818a2fa0-ffffffff818a30c3: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff819748ae)
Location: drivers/md/md-bitmap.c:1005
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81974140-ffffffff81974245: md_bitmap_unplug.part.0 (STB_LOCAL)
ffffffff81974250-ffffffff81974275: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff819797ac)
Location: drivers/md/md-bitmap.c:1006
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81979040-ffffffff81979147: md_bitmap_unplug.part.0 (STB_LOCAL)
ffffffff81979150-ffffffff81979175: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff8195dde0)
Location: drivers/md/md-bitmap.c:1006
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff8195c370-ffffffff8195c477: md_bitmap_unplug.part.0 (STB_LOCAL)
ffffffff8195c480-ffffffff8195c4a5: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81a0370b)
Location: drivers/md/md-bitmap.c:1006
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81a01b80-ffffffff81a01c87: md_bitmap_unplug.part.0 (STB_LOCAL)
ffffffff81a01c90-ffffffff81a01cb5: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81b6b3f1)
Location: drivers/md/md-bitmap.c:1007
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
Direct callers:
  - drivers/md/md.c:bitmap_store
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81b69b00-ffffffff81b69c1a: md_bitmap_unplug.part.0 (STB_LOCAL)
ffffffff81b69c20-ffffffff81b69c55: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d060a0)
Location: drivers/md/md-bitmap.c:1007
Inline: False
Direct callers:
  - drivers/md/md.c:bitmap_store
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81d060a0-ffffffff81d061f3: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81d6f0c0)
Location: drivers/md/md-bitmap.c:1022
Inline: True
Direct callers:
  - drivers/md/md.c:bitmap_store
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_unplug_fn
```
**Symbols:**

```
ffffffff81d6f0c0-ffffffff81d6f1e4: md_bitmap_unplug.part.0 (STB_LOCAL)
ffffffff81d6f200-ffffffff81d6f235: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81e26300)
Location: drivers/md/md-bitmap.c:1028
Inline: True
Direct callers:
  - drivers/md/md.c:bitmap_store
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_unplug_fn
```
**Symbols:**

```
ffffffff81e26300-ffffffff81e264cc: md_bitmap_unplug.part.0 (STB_LOCAL)
ffffffff81e264e0-ffffffff81e26518: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffff800010af8c78)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffff800010af8c78-ffff800010af8e84: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c0bd8eec)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
c0bd8eec-c0bd9018: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (c000000000be4a40)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
c000000000be4a40-c000000000be4ca4: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffe0006e9998)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffe0006e9998-ffffffe0006e9b12: md_bitmap_unplug (STB_GLOBAL)
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
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81848e20)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81848e20-ffffffff81848f43: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81810480)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81810480-ffffffff818105a3: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff81898450)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff81898450-ffffffff81898573: md_bitmap_unplug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void md_bitmap_unplug(struct bitmap *bitmap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/md-bitmap.c (ffffffff818b55b0)
Location: drivers/md/md-bitmap.c:1009
Inline: True
Direct callers:
  - drivers/md/md-bitmap.c:md_bitmap_resize
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
  - drivers/md/md-bitmap.c:md_bitmap_copy_from_slot
```
**Symbols:**

```
ffffffff818b55b0-ffffffff818b56da: md_bitmap_unplug (STB_GLOBAL)
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
