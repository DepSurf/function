# Function: <code>parse_monolithic_mount_data</code>

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
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8130ad00)
Location: fs/fs_context.c:710
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff8130ad00-ffffffff8130ad25: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8131dce0)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff8131dce0-ffffffff8131dd05: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81357aa0)
Location: fs/fs_context.c:641
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff81357aa0-ffffffff81357ac5: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81364590)
Location: fs/fs_context.c:641
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff81364590-ffffffff813645b5: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8136aff0)
Location: fs/fs_context.c:641
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff8136aff0-ffffffff8136b015: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813b9cb0)
Location: fs/fs_context.c:659
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff813b9cb0-ffffffff813b9cd5: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff8143f790)
Location: fs/fs_context.c:659
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff8143f790-ffffffff8143f7bf: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff814ce480)
Location: fs/fs_context.c:659
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff814ce480-ffffffff814ce4af: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff815046d0)
Location: fs/fs_context.c:681
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff815046d0-ffffffff815046ff: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81539390)
Location: fs/fs_context.c:711
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/namespace.c:path_mount
  - fs/namespace.c:do_new_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff81539390-ffffffff815393bf: parse_monolithic_mount_data (STB_GLOBAL)
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
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffff8000103d5e58)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffff8000103d5e58-ffff8000103d5ea4: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c05afb28)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
c05afb28-c05afb5c: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (c0000000004d9560)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
c0000000004d9560-c0000000004d95d4: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffe00028fd14)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffe00028fd14-ffffffe00028fd50: parse_monolithic_mount_data (STB_GLOBAL)
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
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813162c0)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff813162c0-ffffffff813162e5: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81306eb0)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff81306eb0-ffffffff81306ed5: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff813140b0)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff813140b0-ffffffff813140d5: parse_monolithic_mount_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int parse_monolithic_mount_data(struct fs_context *fc, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs_context.c (ffffffff81325900)
Location: fs/fs_context.c:696
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff81325900-ffffffff81325925: parse_monolithic_mount_data (STB_GLOBAL)
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
