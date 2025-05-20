# Function: <code>ext4_getfsmap_free_fixed_metadata</code>

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
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff812f1f60)
Location: fs/ext4/fsmap.c:406
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
ffffffff812f1f60-ffffffff812f1fc7: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813164e0)
Location: fs/ext4/fsmap.c:406
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
ffffffff813164e0-ffffffff81316547: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81344370)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81344370-ffffffff813443d7: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff8135c4c0)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff8135c4c0-ffffffff8135c527: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81385620)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81385620-ffffffff8138567d: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff8139e070)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff8139e070-ffffffff8139e0cd: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
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
In fs/ext4/fsmap.c (ffffffff813eae20)
Location: fs/ext4/fsmap.c:393
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff813fd0b8)
Location: fs/ext4/fsmap.c:396
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff81403512)
Location: fs/ext4/fsmap.c:396
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff81455c9e)
Location: fs/ext4/fsmap.c:396
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff814d35f3)
Location: fs/ext4/fsmap.c:396
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff8156c1f2)
Location: fs/ext4/fsmap.c:396
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff815a41a8)
Location: fs/ext4/fsmap.c:396
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
In fs/ext4/fsmap.c (ffffffff815dcfe8)
Location: fs/ext4/fsmap.c:396
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
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
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffff800010471608)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffff800010471608-ffff80001047167c: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (c0632590)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
**Symbols:**

```
c0632590-c06325ec: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (c000000000591ec0)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
c000000000591ec0-c000000000591f7c: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffe0002fd826)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffe0002fd826-ffffffe0002fd882: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
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
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81396650)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81396650-ffffffff813966ad: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813870e0)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813870e0-ffffffff8138713d: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff81393fb0)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff81393fb0-ffffffff8139400d: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ext4_getfsmap_free_fixed_metadata(struct list_head *meta_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsmap.c (ffffffff813a8040)
Location: fs/ext4/fsmap.c:393
Inline: False
Direct callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
  - fs/ext4/fsmap.c:ext4_getfsmap_datadev
```
**Symbols:**

```
ffffffff813a8040-ffffffff813a809d: ext4_getfsmap_free_fixed_metadata (STB_LOCAL)
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
