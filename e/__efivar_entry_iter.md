# Function: <code>__efivar_entry_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff816d0fa0)
Location: drivers/firmware/efi/vars.c:1029
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_iter
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff816d0fa0-ffffffff816d10c5: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817347a5)
Location: drivers/firmware/efi/vars.c:1020
Inline: True
Inline callers:
  - drivers/firmware/efi/vars.c:efivar_entry_iter
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81734220-ffffffff81734345: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81767a00)
Location: drivers/firmware/efi/vars.c:1041
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81767a00-ffffffff81767b25: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81786530)
Location: drivers/firmware/efi/vars.c:1041
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81786530-ffffffff81786655: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff817fc990)
Location: drivers/firmware/efi/vars.c:1041
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff817fc990-ffffffff817fcab9: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81846120)
Location: drivers/firmware/efi/vars.c:1041
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81846120-ffffffff81846247: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81872120)
Location: drivers/firmware/efi/vars.c:1098
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81872120-ffffffff81872247: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818b5fa0)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff818b5fa0-ffffffff818b60c9: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818e8900)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff818e8900-ffffffff818e8a29: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bb290)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff819bb290-ffffffff819bb3b9: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819bd440)
Location: drivers/firmware/efi/vars.c:1077
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff819bd440-ffffffff819bd569: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff819a1bd0)
Location: drivers/firmware/efi/vars.c:1077
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff819a1bd0-ffffffff819a1cf9: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81a4eb90)
Location: drivers/firmware/efi/vars.c:1080
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81a4eb90-ffffffff81a4ecb9: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81bbd860)
Location: drivers/firmware/efi/vars.c:1080
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81bbd860-ffffffff81bbd9b7: __efivar_entry_iter (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffff800010b5bc28)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffff800010b5bc28-ffff800010b5bd58: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (c0c3c7a8)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
c0c3c7a8-c0c3c8e0: __efivar_entry_iter (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff8188b680)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff8188b680-ffffffff8188b7a9: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff81843000)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff81843000-ffffffff81843129: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818dd760)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff818dd760-ffffffff818dd889: __efivar_entry_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __efivar_entry_iter(int (*func)(struct efivar_entry *, void *), struct list_head *head, void *data, struct efivar_entry **prev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/vars.c (ffffffff818fa270)
Location: drivers/firmware/efi/vars.c:1085
Inline: True
Direct callers:
  - fs/efivarfs/super.c:efivarfs_kill_sb
  - fs/efivarfs/super.c:efivarfs_fill_super
  - drivers/firmware/efi/efivars.c:efivars_sysfs_exit
```
**Symbols:**

```
ffffffff818fa270-ffffffff818fa399: __efivar_entry_iter (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
