# Function: <code>selinux_sb_mnt_opts_compat</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int selinux_sb_mnt_opts_compat(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2702
Inline: False
```
**Symbols:**

```
ffffffff814dcfd0-ffffffff814dd1b7: selinux_sb_mnt_opts_compat (STB_LOCAL)
ffffffff81be259f-ffffffff81be25f3: selinux_sb_mnt_opts_compat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_sb_mnt_opts_compat(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2695
Inline: False
```
**Symbols:**

```
ffffffff815364a0-ffffffff81536687: selinux_sb_mnt_opts_compat (STB_LOCAL)
ffffffff81cd3ec8-ffffffff81cd3f1c: selinux_sb_mnt_opts_compat.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_sb_mnt_opts_compat(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815cdc70)
Location: security/selinux/hooks.c:2634
Inline: False
```
**Symbols:**

```
ffffffff815cdc70-ffffffff815cddaf: selinux_sb_mnt_opts_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_sb_mnt_opts_compat(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8167b650)
Location: security/selinux/hooks.c:2633
Inline: False
```
**Symbols:**

```
ffffffff8167b650-ffffffff8167b78f: selinux_sb_mnt_opts_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_sb_mnt_opts_compat(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816b3710)
Location: security/selinux/hooks.c:2612
Inline: False
```
**Symbols:**

```
ffffffff816b3710-ffffffff816b384f: selinux_sb_mnt_opts_compat (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_sb_mnt_opts_compat(struct super_block *sb, void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816f0010)
Location: security/selinux/hooks.c:2662
Inline: False
```
**Symbols:**

```
ffffffff816f0010-ffffffff816f0150: selinux_sb_mnt_opts_compat (STB_LOCAL)
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
