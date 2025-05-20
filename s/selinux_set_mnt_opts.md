# Function: <code>selinux_set_mnt_opts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81345b60)
Location: security/selinux/hooks.c:615
Inline: False
```
**Symbols:**

```
ffffffff81345b60-ffffffff813461b6: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137b2a0)
Location: security/selinux/hooks.c:687
Inline: False
```
**Symbols:**

```
ffffffff8137b2a0-ffffffff8137b905: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813916e0)
Location: security/selinux/hooks.c:688
Inline: False
```
**Symbols:**

```
ffffffff813916e0-ffffffff81391d45: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a7cc0)
Location: security/selinux/hooks.c:635
Inline: False
```
**Symbols:**

```
ffffffff813a7cc0-ffffffff813a8347: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cd440)
Location: security/selinux/hooks.c:636
Inline: False
```
**Symbols:**

```
ffffffff813cd440-ffffffff813cdaed: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, struct security_mnt_opts *opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:718
Inline: False
```
**Symbols:**

```
ffffffff813ff4d0-ffffffff813ffb62: selinux_set_mnt_opts (STB_LOCAL)
ffffffff81402be7-ffffffff81402c5c: selinux_set_mnt_opts.cold.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:621
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff8141b600-ffffffff8141bcab: selinux_set_mnt_opts (STB_LOCAL)
ffffffff8141e790-ffffffff8141e7c9: selinux_set_mnt_opts.cold.76 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:644
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff81448fe0-ffffffff81449656: selinux_set_mnt_opts (STB_LOCAL)
ffffffff8144c3a3-ffffffff8144c41b: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff81462b70-ffffffff814631ee: selinux_set_mnt_opts (STB_LOCAL)
ffffffff81466193-ffffffff8146620b: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:595
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff814b9540-ffffffff814b9c2b: selinux_set_mnt_opts (STB_LOCAL)
ffffffff814b9f06-ffffffff814ba00e: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:596
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff814d7280-ffffffff814d7983: selinux_set_mnt_opts (STB_LOCAL)
ffffffff81bf03b0-ffffffff81bf04b8: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:652
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff814dade0-ffffffff814db497: selinux_set_mnt_opts (STB_LOCAL)
ffffffff81be23ba-ffffffff81be24c2: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:630
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff81533cf0-ffffffff815343b4: selinux_set_mnt_opts (STB_LOCAL)
ffffffff81cd3be0-ffffffff81cd3d05: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:602
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff815cddb0-ffffffff815ce42b: selinux_set_mnt_opts (STB_LOCAL)
ffffffff81e86f33-ffffffff81e86fb1: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:604
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff8167b7a0-ffffffff8167be2b: selinux_set_mnt_opts (STB_LOCAL)
ffffffff8207392e-ffffffff82073949: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:596
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff816b3860-ffffffff816b3ff4: selinux_set_mnt_opts (STB_LOCAL)
ffffffff820f351c-ffffffff820f3531: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:637
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff816f0320-ffffffff816f0b34: selinux_set_mnt_opts (STB_LOCAL)
ffffffff821d06b4-ffffffff821d070f: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff800010550a40)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffff800010550a40-ffff800010551014: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0703524)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
c0703524-c0703bd4: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a6aa0)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
c0000000006a6aa0-c0000000006a7da8: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a9f0c)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffe0003a9f0c-ffffffe0003aa434: selinux_set_mnt_opts (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff8145b150-ffffffff8145b7ce: selinux_set_mnt_opts (STB_LOCAL)
ffffffff8145e773-ffffffff8145e7eb: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff8144bb80-ffffffff8144c1fe: selinux_set_mnt_opts (STB_LOCAL)
ffffffff8144f1a3-ffffffff8144f21b: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff814571f0-ffffffff8145786e: selinux_set_mnt_opts (STB_LOCAL)
ffffffff8145a813-ffffffff8145a88b: selinux_set_mnt_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int selinux_set_mnt_opts(struct super_block *sb, void *mnt_opts, long unsigned int kern_flags, long unsigned int *set_kern_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:646
Inline: False
Direct callers:
  - security/selinux/hooks.c:delayed_superblock_init
```
**Symbols:**

```
ffffffff8146c170-ffffffff8146c7ee: selinux_set_mnt_opts (STB_LOCAL)
ffffffff81471f8e-ffffffff81472006: selinux_set_mnt_opts.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *mnt_opts</code>
</li>
<li>
<b>Param removed. </b>
<code>struct security_mnt_opts *opts</code>
</li>
</ul>
</details>
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
