# Function: <code>selinux_fs_info_free</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81404240)
Location: security/selinux/selinuxfs.c:100
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff81404240-ffffffff814042ae: selinux_fs_info_free.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8141fee0)
Location: security/selinux/selinuxfs.c:100
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff8141fee0-ffffffff8141ff4e: selinux_fs_info_free.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8144db30)
Location: security/selinux/selinuxfs.c:99
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff8144db30-ffffffff8144db9e: selinux_fs_info_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81467950)
Location: security/selinux/selinuxfs.c:99
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff81467950-ffffffff814679be: selinux_fs_info_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814ba090)
Location: security/selinux/selinuxfs.c:99
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff814ba090-ffffffff814ba108: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814d7a90)
Location: security/selinux/selinuxfs.c:98
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff814d7a90-ffffffff814d7b08: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff814de400)
Location: security/selinux/selinuxfs.c:99
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff814de400-ffffffff814de478: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff815372b0)
Location: security/selinux/selinuxfs.c:99
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff815372b0-ffffffff81537328: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff815ce560)
Location: security/selinux/selinuxfs.c:99
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff815ce560-ffffffff815ce5e2: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8167bfb0)
Location: security/selinux/selinuxfs.c:99
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff8167bfb0-ffffffff8167c032: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816b4120)
Location: security/selinux/selinuxfs.c:97
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff816b4120-ffffffff816b41a2: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff816f0c90)
Location: security/selinux/selinuxfs.c:97
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff816f0c90-ffffffff816f0d0e: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffff800010555d00)
Location: security/selinux/selinuxfs.c:99
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffff800010555d00-ffff800010555d7c: selinux_fs_info_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0709708)
Location: security/selinux/selinuxfs.c:99
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
c0709708-c0709780: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (c0000000006b1460)
Location: security/selinux/selinuxfs.c:99
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
c0000000006b1460-c0000000006b1524: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selinux_fs_info_free(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffe0003acaf0)
Location: security/selinux/selinuxfs.c:99
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffe0003acaf0-ffffffe0003acb70: selinux_fs_info_free (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8145ff30)
Location: security/selinux/selinuxfs.c:99
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff8145ff30-ffffffff8145ff9e: selinux_fs_info_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81450960)
Location: security/selinux/selinuxfs.c:99
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff81450960-ffffffff814509ce: selinux_fs_info_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff8145bfd0)
Location: security/selinux/selinuxfs.c:99
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff8145bfd0-ffffffff8145c03e: selinux_fs_info_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/selinuxfs.c (ffffffff81473770)
Location: security/selinux/selinuxfs.c:99
Inline: True
Direct callers:
  - security/selinux/selinuxfs.c:sel_kill_sb
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff81473770-ffffffff814737de: selinux_fs_info_free.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
