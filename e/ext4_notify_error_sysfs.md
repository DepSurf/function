# Function: <code>ext4_notify_error_sysfs</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_notify_error_sysfs(struct ext4_sb_info *sbi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/sysfs.c (ffffffff814a7b20)
Location: fs/ext4/sysfs.c:509
Inline: False
Direct callers:
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff814a7b20-ffffffff814a7b40: ext4_notify_error_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_notify_error_sysfs(struct ext4_sb_info *sbi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/sysfs.c (ffffffff8152f3c0)
Location: fs/ext4/sysfs.c:511
Inline: False
Direct callers:
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff8152f3c0-ffffffff8152f3ea: ext4_notify_error_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_notify_error_sysfs(struct ext4_sb_info *sbi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/sysfs.c (ffffffff815cd5b0)
Location: fs/ext4/sysfs.c:516
Inline: False
Direct callers:
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff815cd5b0-ffffffff815cd5da: ext4_notify_error_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_notify_error_sysfs(struct ext4_sb_info *sbi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/sysfs.c (ffffffff81605090)
Location: fs/ext4/sysfs.c:516
Inline: False
Direct callers:
  - fs/ext4/super.c:flush_stashed_error_work
  - fs/ext4/super.c:flush_stashed_error_work
```
**Symbols:**

```
ffffffff81605090-ffffffff816050ba: ext4_notify_error_sysfs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_notify_error_sysfs(struct ext4_sb_info *sbi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/sysfs.c (ffffffff8163dd50)
Location: fs/ext4/sysfs.c:516
Inline: False
Direct callers:
  - fs/ext4/super.c:update_super_work
```
**Symbols:**

```
ffffffff8163dd50-ffffffff8163dd7a: ext4_notify_error_sysfs (STB_GLOBAL)
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
