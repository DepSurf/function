# Function: <code>ext4_load_and_init_journal</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_load_and_init_journal(struct super_block *sb, struct ext4_super_block *es, struct ext4_fs_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c77a0)
Location: fs/ext4/super.c:4813
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff815c77a0-ffffffff815c7b34: ext4_load_and_init_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_load_and_init_journal(struct super_block *sb, struct ext4_super_block *es, struct ext4_fs_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815ff5e0)
Location: fs/ext4/super.c:4893
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff815ff5e0-ffffffff815ff94e: ext4_load_and_init_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_load_and_init_journal(struct super_block *sb, struct ext4_super_block *es, struct ext4_fs_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81638300)
Location: fs/ext4/super.c:4899
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
```
**Symbols:**

```
ffffffff81638300-ffffffff8163866e: ext4_load_and_init_journal (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
