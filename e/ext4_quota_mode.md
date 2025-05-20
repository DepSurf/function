# Function: <code>ext4_quota_mode</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_quota_mode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8143e630)
Location: fs/ext4/super.c:3991
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8143e630-ffffffff8143e6a2: ext4_quota_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_quota_mode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81444760)
Location: fs/ext4/super.c:4021
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81444760-ffffffff814447d2: ext4_quota_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_quota_mode(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81498560)
Location: fs/ext4/super.c:3843
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81498560-ffffffff814985d2: ext4_quota_mode (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff8152bbf1)
Location: fs/ext4/super.c:4240
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff815cac31)
Location: fs/ext4/super.c:4228
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff81602ce5)
Location: fs/ext4/super.c:4279
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff8163bb45)
Location: fs/ext4/super.c:4285
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_reconfigure
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
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
</ul>
