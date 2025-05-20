# Function: <code>ext4_getfsmap_find_fixed_metadata</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff812f28a0)
Location: fs/ext4/fsmap.c:418
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff812f28a0-ffffffff812f2c91: ext4_getfsmap_find_fixed_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81316e30)
Location: fs/ext4/fsmap.c:418
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81316e30-ffffffff81317221: ext4_getfsmap_find_fixed_metadata (STB_GLOBAL)
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
In fs/ext4/fsmap.c (ffffffff81344d3b)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff8135ce8b)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff8138601d)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff8139ea6d)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813ea930)
Location: fs/ext4/fsmap.c:405
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813ea930-ffffffff813eabd0: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813fcbe0)
Location: fs/ext4/fsmap.c:408
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813fcbe0-ffffffff813fce80: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81402830)
Location: fs/ext4/fsmap.c:408
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81402830-ffffffff81402c4f: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81454f00)
Location: fs/ext4/fsmap.c:408
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81454f00-ffffffff8145531f: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff814d2740)
Location: fs/ext4/fsmap.c:408
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff814d2740-ffffffff814d2b7a: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff8156b2e0)
Location: fs/ext4/fsmap.c:408
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff8156b2e0-ffffffff8156b71a: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff815a31a0)
Location: fs/ext4/fsmap.c:408
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff815a31a0-ffffffff815a35cf: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff815dbec0)
Location: fs/ext4/fsmap.c:408
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff815dbec0-ffffffff815dc406: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
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
In fs/ext4/fsmap.c (ffff800010471fbc)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_getfsmap_find_fixed_metadata(struct super_block *sb, struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (c0632ff8)
Location: fs/ext4/fsmap.c:405
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
c0632ff8-c0633484: ext4_getfsmap_find_fixed_metadata (STB_LOCAL)
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
In fs/ext4/fsmap.c (c000000000592b74)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffe0002fdf96)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff8139704d)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff81387add)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff813949ad)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
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
In fs/ext4/fsmap.c (ffffffff813a8a9d)
Location: fs/ext4/fsmap.c:405
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
</ul>
