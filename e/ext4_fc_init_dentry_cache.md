# Function: <code>ext4_fc_init_dentry_cache</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_fc_init_dentry_cache();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff82ff0805)
Location: fs/ext4/fast_commit.c:2176
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
```
**Symbols:**

```
ffffffff82ff0805-ffffffff82ff083e: ext4_fc_init_dentry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_fc_init_dentry_cache();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff831fb0ac)
Location: fs/ext4/fast_commit.c:2181
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
```
**Symbols:**

```
ffffffff831fb0ac-ffffffff831fb0e5: ext4_fc_init_dentry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_fc_init_dentry_cache();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff832e2012)
Location: fs/ext4/fast_commit.c:2164
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
```
**Symbols:**

```
ffffffff832e2012-ffffffff832e204b: ext4_fc_init_dentry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_fc_init_dentry_cache();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff83498213)
Location: fs/ext4/fast_commit.c:2248
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
```
**Symbols:**

```
ffffffff83498213-ffffffff8349825b: ext4_fc_init_dentry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_fc_init_dentry_cache();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff83ecda60)
Location: fs/ext4/fast_commit.c:2290
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
```
**Symbols:**

```
ffffffff83ecda60-ffffffff83ecdaa8: ext4_fc_init_dentry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_fc_init_dentry_cache();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff836f2b00)
Location: fs/ext4/fast_commit.c:2290
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
```
**Symbols:**

```
ffffffff836f2b00-ffffffff836f2b48: ext4_fc_init_dentry_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_fc_init_dentry_cache();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff83925cd0)
Location: fs/ext4/fast_commit.c:2290
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
```
**Symbols:**

```
ffffffff83925cd0-ffffffff83925d18: ext4_fc_init_dentry_cache (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
