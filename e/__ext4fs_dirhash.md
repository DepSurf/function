# Function: <code>__ext4fs_dirhash</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81387020)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff81387020-ffffffff81387561: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff8139fa70)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff8139fa70-ffffffff8139ffb1: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff813ebb70)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff813ebb70-ffffffff813ebe51: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff813fdd30)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff813fdd30-ffffffff813fe011: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ext4fs_dirhash(const struct inode *dir, const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81404190)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff81404190-ffffffff814044ee: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ext4fs_dirhash(const struct inode *dir, const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81456940)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff81456940-ffffffff81456c9e: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4fs_dirhash(const struct inode *dir, const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff814d43b0)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff814d43b0-ffffffff814d4725: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4fs_dirhash(const struct inode *dir, const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff8156d070)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff8156d070-ffffffff8156d3dd: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4fs_dirhash(const struct inode *dir, const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff815a4f30)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff815a4f30-ffffffff815a52cb: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4fs_dirhash(const struct inode *dir, const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff815ddd70)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff815ddd70-ffffffff815de10b: __ext4fs_dirhash (STB_LOCAL)
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
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffff800010472f10)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffff800010472f10-ffff8000104734d8: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (c0634324)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
c0634324-c06349ac: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (c000000000593ee0)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
c000000000593ee0-c00000000059471c: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffe0002fecd8)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffe0002fecd8-ffffffe0002ff30c: __ext4fs_dirhash (STB_LOCAL)
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
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81398050)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff81398050-ffffffff81398591: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff81388ae0)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff81388ae0-ffffffff81389021: __ext4fs_dirhash (STB_LOCAL)
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
In fs/ext4/hash.c (ffffffff813959fb)
Location: fs/ext4/hash.c:200
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __ext4fs_dirhash(const char *name, int len, struct dx_hash_info *hinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/hash.c (ffffffff813a9b00)
Location: fs/ext4/hash.c:200
Inline: False
Direct callers:
  - fs/ext4/hash.c:ext4fs_dirhash
  - fs/ext4/hash.c:ext4fs_dirhash
```
**Symbols:**

```
ffffffff813a9b00-ffffffff813aa041: __ext4fs_dirhash (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct inode *dir</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, len, hinfo</code> ➡️ <code>dir, name, len, hinfo</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
