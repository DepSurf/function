# Function: <code>__ext4_remount</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ext4_remount(struct fs_context *fc, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8152b1e0)
Location: fs/ext4/super.c:6178
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_reconfigure
```
**Symbols:**

```
ffffffff8152b1e0-ffffffff8152bbab: __ext4_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ext4_remount(struct fs_context *fc, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ca210)
Location: fs/ext4/super.c:6330
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_reconfigure
```
**Symbols:**

```
ffffffff815ca210-ffffffff815cabdb: __ext4_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ext4_remount(struct fs_context *fc, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff816020a0)
Location: fs/ext4/super.c:6419
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_reconfigure
```
**Symbols:**

```
ffffffff816020a0-ffffffff81602c8f: __ext4_remount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ext4_remount(struct fs_context *fc, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8163ae40)
Location: fs/ext4/super.c:6436
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_reconfigure
```
**Symbols:**

```
ffffffff8163ae40-ffffffff8163bae8: __ext4_remount (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
