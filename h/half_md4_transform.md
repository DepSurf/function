# Function: <code>half_md4_transform</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__u32 half_md4_transform(__u32 *buf, const __u32 *in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/halfmd4.c (ffffffff813f8500)
Location: lib/halfmd4.c:26
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff813f8500-ffffffff813f87a7: half_md4_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__u32 half_md4_transform(__u32 *buf, const __u32 *in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/halfmd4.c (ffffffff8143f3a0)
Location: lib/halfmd4.c:26
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff8143f3a0-ffffffff8143f63a: half_md4_transform (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__u32 half_md4_transform(__u32 *buf, const __u32 *in);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/halfmd4.c (ffffffff8145c4a0)
Location: lib/halfmd4.c:26
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff8145c4a0-ffffffff8145c73a: half_md4_transform (STB_GLOBAL)
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
In fs/ext4/hash.c (ffffffff812f394c)
Location: fs/ext4/hash.c:56
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
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
In fs/ext4/hash.c (ffffffff81317f04)
Location: fs/ext4/hash.c:56
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
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
In fs/ext4/hash.c (ffffffff81345f4a)
Location: fs/ext4/hash.c:52
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
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
In fs/ext4/hash.c (ffffffff8135e088)
Location: fs/ext4/hash.c:52
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff8138726b)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff8139fcbb)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/hash.c (ffffffff813eb8c0)
Location: fs/ext4/hash.c:53
Inline: True
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff813eb8c0-ffffffff813ebb66: half_md4_transform.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/hash.c (ffffffff813fda80)
Location: fs/ext4/hash.c:53
Inline: True
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff813fda80-ffffffff813fdd26: half_md4_transform.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__u32 half_md4_transform(__u32 *buf, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81403d80)
Location: fs/ext4/hash.c:53
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff81403d80-ffffffff81404028: half_md4_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__u32 half_md4_transform(__u32 *buf, const __u32 *in);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81456530)
Location: fs/ext4/hash.c:53
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff81456530-ffffffff814567d8: half_md4_transform (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/hash.c (ffffffff814d40e0)
Location: fs/ext4/hash.c:53
Inline: True
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff814d40e0-ffffffff814d43a4: half_md4_transform.isra.0 (STB_LOCAL)
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
In fs/ext4/hash.c (ffffffff8156cd90)
Location: fs/ext4/hash.c:53
Inline: True
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff8156cd90-ffffffff8156d054: half_md4_transform.isra.0 (STB_LOCAL)
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
In fs/ext4/hash.c (ffffffff815a4c50)
Location: fs/ext4/hash.c:53
Inline: True
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff815a4c50-ffffffff815a4f14: half_md4_transform.isra.0 (STB_LOCAL)
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
In fs/ext4/hash.c (ffffffff815dda90)
Location: fs/ext4/hash.c:53
Inline: True
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff815dda90-ffffffff815ddd54: half_md4_transform.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffff80001047318c)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (c0634560)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (c000000000594060)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffe0002fed72)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff8139829b)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81388d2b)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81395c02)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff813a9d4b)
Location: fs/ext4/hash.c:53
Inline: True
Inline callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
