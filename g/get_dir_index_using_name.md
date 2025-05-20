# Function: <code>get_dir_index_using_name</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff81323a69)
Location: fs/squashfs/namei.c:76
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff813398f9)
Location: fs/squashfs/namei.c:76
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff8134e5d5)
Location: fs/squashfs/namei.c:76
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff81372c85)
Location: fs/squashfs/namei.c:76
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff813a15e7)
Location: fs/squashfs/namei.c:76
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff813ba3c7)
Location: fs/squashfs/namei.c:76
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff813e4c98)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff813fece8)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int get_dir_index_using_name(struct super_block *sb, u64 *next_block, int *next_offset, u64 index_start, int index_offset, int i_count, const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:63
Inline: False
Direct callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff8144c530-ffffffff8144c6c5: get_dir_index_using_name (STB_LOCAL)
ffffffff8144c96d-ffffffff8144c984: get_dir_index_using_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int get_dir_index_using_name(struct super_block *sb, u64 *next_block, int *next_offset, u64 index_start, int index_offset, int i_count, const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:63
Inline: False
Direct callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff81468be0-ffffffff81468d75: get_dir_index_using_name (STB_LOCAL)
ffffffff81bed503-ffffffff81bed51a: get_dir_index_using_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int get_dir_index_using_name(struct super_block *sb, u64 *next_block, int *next_offset, u64 index_start, int index_offset, int i_count, const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:63
Inline: False
Direct callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff8146e2e0-ffffffff8146e475: get_dir_index_using_name (STB_LOCAL)
ffffffff81bdf5e5-ffffffff81bdf5fc: get_dir_index_using_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int get_dir_index_using_name(struct super_block *sb, u64 *next_block, int *next_offset, u64 index_start, int index_offset, int i_count, const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:63
Inline: False
Direct callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff814c4b70-ffffffff814c4d05: get_dir_index_using_name (STB_LOCAL)
ffffffff81ccf0c4-ffffffff81ccf0db: get_dir_index_using_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int get_dir_index_using_name(struct super_block *sb, u64 *next_block, int *next_offset, u64 index_start, int index_offset, int i_count, const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/squashfs/namei.c (0)
Location: fs/squashfs/namei.c:63
Inline: False
Direct callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff8154f970-ffffffff8154fb16: get_dir_index_using_name (STB_LOCAL)
ffffffff81e8213f-ffffffff81e82161: get_dir_index_using_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_dir_index_using_name(struct super_block *sb, u64 *next_block, int *next_offset, u64 index_start, int index_offset, int i_count, const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff815f0420)
Location: fs/squashfs/namei.c:63
Inline: False
Direct callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff815f0420-ffffffff815f05e5: get_dir_index_using_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_dir_index_using_name(struct super_block *sb, u64 *next_block, int *next_offset, u64 index_start, int index_offset, int i_count, const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff81628460)
Location: fs/squashfs/namei.c:63
Inline: False
Direct callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff81628460-ffffffff81628625: get_dir_index_using_name (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_dir_index_using_name(struct super_block *sb, u64 *next_block, int *next_offset, u64 index_start, int index_offset, int i_count, const char *name, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/squashfs/namei.c (ffffffff816615e0)
Location: fs/squashfs/namei.c:63
Inline: False
Direct callers:
  - fs/squashfs/namei.c:squashfs_lookup
```
**Symbols:**

```
ffffffff816615e0-ffffffff816617d4: get_dir_index_using_name (STB_LOCAL)
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
In fs/squashfs/namei.c (ffff8000104dcdb8)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (c069e7d8)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (c000000000618454)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffe000351876)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff813f72c8)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff813e7d48)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff813f4648)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
In fs/squashfs/namei.c (ffffffff8140a278)
Location: fs/squashfs/namei.c:63
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
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
