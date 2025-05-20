# Function: <code>ext4_mb_init_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812cf430)
Location: fs/ext4/mballoc.c:1045
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy
  - fs/ext4/mballoc.c:ext4_trim_fs
```
**Symbols:**

```
ffffffff812cf430-ffffffff812cf638: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812fedc0)
Location: fs/ext4/mballoc.c:1045
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff812fedc0-ffffffff812ff055: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81314e30)
Location: fs/ext4/mballoc.c:1045
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff81314e30-ffffffff813150d5: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8130c300)
Location: fs/ext4/mballoc.c:1043
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff8130c300-ffffffff8130c54e: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81330e60)
Location: fs/ext4/mballoc.c:1043
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff81330e60-ffffffff81331117: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8135f400)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff8135f400-ffffffff8135f6ca: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813778a0)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff813778a0-ffffffff81377b6a: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a0d10)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff813a0d10-ffffffff813a0fe1: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b9b80)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff813b9b80-ffffffff813b9e61: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814056f0)
Location: fs/ext4/mballoc.c:1093
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff814056f0-ffffffff81405924: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81418960)
Location: fs/ext4/mballoc.c:1072
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff81418960-ffffffff81418b95: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141f190)
Location: fs/ext4/mballoc.c:1406
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff8141f190-ffffffff8141f451: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1410
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff814728b0-ffffffff81472b7b: ext4_mb_init_group (STB_LOCAL)
ffffffff81ccbc9c-ffffffff81ccbcc0: ext4_mb_init_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1407
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff814f3880-ffffffff814f3c74: ext4_mb_init_group (STB_LOCAL)
ffffffff81e7ec61-ffffffff81e7ec8b: ext4_mb_init_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:1364
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff8158de70-ffffffff8158e246: ext4_mb_init_group (STB_LOCAL)
ffffffff8206f10b-ffffffff8206f135: ext4_mb_init_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c4840)
Location: fs/ext4/mballoc.c:1487
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff815c4840-ffffffff815c4bd5: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815fcad0)
Location: fs/ext4/mballoc.c:1503
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_prefetch_fini
  - fs/ext4/mballoc.c:ext4_mb_good_group_nolock
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff815fcad0-ffffffff815fce59: ext4_mb_init_group (STB_LOCAL)
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
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff800010490408)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffff800010490408-ffff8000104906a0: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0651560)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
c0651560-c06517dc: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005b78d0)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
c0000000005b78d0-c0000000005b7d00: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe00031542e)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffe00031542e-ffffffe000315632: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b2160)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff813b2160-ffffffff813b2441: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a2bf0)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff813a2bf0-ffffffff813a2ed1: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813af9c0)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff813af9c0-ffffffff813afca1: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_mb_init_group(struct super_block *sb, ext4_group_t group, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c43f0)
Location: fs/ext4/mballoc.c:1032
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_mb_good_group
  - fs/ext4/mballoc.c:ext4_mb_load_buddy_gfp
```
**Symbols:**

```
ffffffff813c43f0-ffffffff813c46d8: ext4_mb_init_group (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
