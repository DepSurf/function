# Function: <code>smk_access_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81362660)
Location: security/smack/smack_access.c:90
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_access
  - security/smack/smack_access.c:smk_tskacc
Direct callers:
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff81362660-ffffffff813626a9: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81398fc3)
Location: security/smack/smack_access.c:90
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff81398830-ffffffff8139887c: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813afba3)
Location: security/smack/smack_access.c:85
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff813af410-ffffffff813af45c: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813c6762)
Location: security/smack/smack_access.c:85
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff813c5fb0-ffffffff813c5ff9: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff813eca52)
Location: security/smack/smack_access.c:85
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff813ec2a0-ffffffff813ec2e9: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8141d893)
Location: security/smack/smack_access.c:85
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff8141d0d0-ffffffff8141d119: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81439e83)
Location: security/smack/smack_access.c:85
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff814396c0-ffffffff81439709: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81467a43)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff814672e0-ffffffff81467324: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81481823)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff814810c0-ffffffff81481104: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814d77f3)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff814d7020-ffffffff814d7067: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814f4d6b)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff814f4490-ffffffff814f44d7: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff814fbcdb)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff814fb400-ffffffff814fb444: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8155694b)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff81556070-ffffffff815560b5: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff815f0d6b)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff815f03e0-ffffffff815f043d: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816a11db)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff816a07b0-ffffffff816a080d: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff816d9b1b)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff816d90f0-ffffffff816d914d: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff817165bb)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff81715b50-ffffffff81715bad: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffff800010573284)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffff8000105728e0-ffff800010572974: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c07263c8)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
c0725b50-c0725bb8: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (c0000000006db564)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
c0000000006da720-c0000000006da798: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffe0003c6744)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffe0003c5f5e-ffffffe0003c5fc6: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81479e03)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff814796a0-ffffffff814796e4: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8146a823)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff8146a0c0-ffffffff8146a104: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff81475ea3)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff81475740-ffffffff81475784: smk_access_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int smk_access_entry(char *subject_label, char *object_label, struct list_head *rule_list);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_access.c (ffffffff8148d923)
Location: security/smack/smack_access.c:81
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_tskacc
  - security/smack/smack_access.c:smk_access
Direct callers:
  - security/smack/smack_lsm.c:smack_dentry_create_files_as
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_init_security
```
**Symbols:**

```
ffffffff8148d140-ffffffff8148d184: smk_access_entry (STB_GLOBAL)
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
