# Function: <code>do_remount_sb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_remount_sb(struct super_block *sb, int flags, void *data, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81210270)
Location: fs/super.c:747
Inline: False
Direct callers:
  - fs/super.c:do_emergency_remount
  - fs/super.c:mount_single
  - fs/namespace.c:do_umount
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff81210270-ffffffff81210451: do_remount_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_remount_sb(struct super_block *sb, int flags, void *data, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81236d40)
Location: fs/super.c:761
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff81236d40-ffffffff81236f23: do_remount_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_remount_sb(struct super_block *sb, int flags, void *data, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812499f0)
Location: fs/super.c:807
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff812499f0-ffffffff81249bd3: do_remount_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_remount_sb(struct super_block *sb, int flags, void *data, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81255320)
Location: fs/super.c:810
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff81255320-ffffffff812554cd: do_remount_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_remount_sb(struct super_block *sb, int sb_flags, void *data, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812774b0)
Location: fs/super.c:810
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount
  - fs/namespace.c:do_mount
  - fs/namespace.c:do_umount
```
**Symbols:**

```
ffffffff812774b0-ffffffff81277660: do_remount_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_remount_sb(struct super_block *sb, int sb_flags, void *data, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129de70)
Location: fs/super.c:842
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff8129de70-ffffffff8129e045: do_remount_sb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_remount_sb(struct super_block *sb, int sb_flags, void *data, int force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b2e30)
Location: fs/super.c:846
Inline: False
Direct callers:
  - fs/super.c:mount_single
  - fs/super.c:do_emergency_remount_callback
  - fs/namespace.c:do_mount
  - fs/namespace.c:ksys_umount
```
**Symbols:**

```
ffffffff812b2e30-ffffffff812b3005: do_remount_sb (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int sb_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
