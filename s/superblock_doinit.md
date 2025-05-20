# Function: <code>superblock_doinit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int superblock_doinit(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81348150)
Location: security/selinux/hooks.c:1072
Inline: True
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
  - security/selinux/hooks.c:selinux_sb_kern_mount
```
**Symbols:**

```
ffffffff81348150-ffffffff81348234: superblock_doinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int superblock_doinit(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137f170)
Location: security/selinux/hooks.c:1143
Inline: True
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
  - security/selinux/hooks.c:selinux_sb_kern_mount
```
**Symbols:**

```
ffffffff8137f170-ffffffff8137f254: superblock_doinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int superblock_doinit(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81395c00)
Location: security/selinux/hooks.c:1145
Inline: True
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
  - security/selinux/hooks.c:selinux_sb_kern_mount
```
**Symbols:**

```
ffffffff81395c00-ffffffff81395ce4: superblock_doinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int superblock_doinit(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813abd00)
Location: security/selinux/hooks.c:1123
Inline: True
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
  - security/selinux/hooks.c:selinux_sb_kern_mount
```
**Symbols:**

```
ffffffff813abd00-ffffffff813abde4: superblock_doinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int superblock_doinit(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813d1d70)
Location: security/selinux/hooks.c:1126
Inline: True
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
  - security/selinux/hooks.c:selinux_sb_kern_mount
```
**Symbols:**

```
ffffffff813d1d70-ffffffff813d1e54: superblock_doinit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int superblock_doinit(struct super_block *sb, void *data);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813ffb70)
Location: security/selinux/hooks.c:1208
Inline: True
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
  - security/selinux/hooks.c:selinux_sb_kern_mount
```
**Symbols:**

```
ffffffff813ffb70-ffffffff813ffc54: superblock_doinit (STB_LOCAL)
```
</details>
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
