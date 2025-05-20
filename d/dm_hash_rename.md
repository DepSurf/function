# Function: <code>dm_hash_rename</code>

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
In drivers/md/dm-ioctl.c (ffffffff816a99e6)
Location: drivers/md/dm-ioctl.c:368
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff81709e45)
Location: drivers/md/dm-ioctl.c:368
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff8173bd15)
Location: drivers/md/dm-ioctl.c:368
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff817555d0)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff817c7870)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff818109b9)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff8183c9b9)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff8187f0a4)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff818b0f24)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct mapped_device *dm_hash_rename(struct dm_ioctl *param, const char *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:369
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff81980e40-ffffffff819810b0: dm_hash_rename (STB_LOCAL)
ffffffff819829f8-ffffffff81982acc: dm_hash_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct mapped_device *dm_hash_rename(struct dm_ioctl *param, const char *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:369
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff81985460-ffffffff819856d0: dm_hash_rename (STB_LOCAL)
ffffffff81c28336-ffffffff81c2840a: dm_hash_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct mapped_device *dm_hash_rename(struct dm_ioctl *param, const char *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:406
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff81969cb0-ffffffff81969f14: dm_hash_rename (STB_LOCAL)
ffffffff81c1a579-ffffffff81c1a619: dm_hash_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct mapped_device *dm_hash_rename(struct dm_ioctl *param, const char *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:408
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff81a12140-ffffffff81a123b8: dm_hash_rename (STB_LOCAL)
ffffffff81d2a3cc-ffffffff81d2a480: dm_hash_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct mapped_device *dm_hash_rename(struct dm_ioctl *param, const char *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:409
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff81b7a950-ffffffff81b7abad: dm_hash_rename (STB_LOCAL)
ffffffff81ef65e6-ffffffff81ef66d7: dm_hash_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct mapped_device *dm_hash_rename(struct dm_ioctl *param, const char *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:409
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff81d19b70-ffffffff81d19ea6: dm_hash_rename (STB_LOCAL)
ffffffff820a8720-ffffffff820a8734: dm_hash_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct mapped_device *dm_hash_rename(struct dm_ioctl *param, const char *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:426
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff81d82cd0-ffffffff81d8300d: dm_hash_rename (STB_LOCAL)
ffffffff82129935-ffffffff82129949: dm_hash_rename.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct mapped_device *dm_hash_rename(struct dm_ioctl *param, const char *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ioctl.c (0)
Location: drivers/md/dm-ioctl.c:426
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
**Symbols:**

```
ffffffff81e3a390-ffffffff81e3a6cd: dm_hash_rename (STB_LOCAL)
ffffffff8220b684-ffffffff8220b698: dm_hash_rename.cold (STB_LOCAL)
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
In drivers/md/dm-ioctl.c (ffff800010b08190)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (c0be6f78)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (c000000000bf9624)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffe0006f690a)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff81856da4)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff8181e3b4)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff818a63d4)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
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
In drivers/md/dm-ioctl.c (ffffffff818c2614)
Location: drivers/md/dm-ioctl.c:369
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dev_rename
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
