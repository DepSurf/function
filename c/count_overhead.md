# Function: <code>count_overhead</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812bb707)
Location: fs/ext4/super.c:2996
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff812ea6a7)
Location: fs/ext4/super.c:3147
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8130044e)
Location: fs/ext4/super.c:3195
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81335296)
Location: fs/ext4/super.c:3274
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8135979c)
Location: fs/ext4/super.c:3273
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81388128)
Location: fs/ext4/super.c:3348
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813a0cf8)
Location: fs/ext4/super.c:3412
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cb5a8)
Location: fs/ext4/super.c:3448
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e4968)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int count_overhead(struct super_block *sb, ext4_group_t grp, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142cbb0)
Location: fs/ext4/super.c:3614
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff8142cbb0-ffffffff8142cee0: count_overhead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int count_overhead(struct super_block *sb, ext4_group_t grp, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814459b0)
Location: fs/ext4/super.c:3840
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff814459b0-ffffffff81445ce2: count_overhead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int count_overhead(struct super_block *sb, ext4_group_t grp, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144b280)
Location: fs/ext4/super.c:3870
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff8144b280-ffffffff8144b5ac: count_overhead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int count_overhead(struct super_block *sb, ext4_group_t grp, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:3692
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff8149f1f0-ffffffff8149f55b: count_overhead (STB_LOCAL)
ffffffff81ccd7d7-ffffffff81ccd8a8: count_overhead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int count_overhead(struct super_block *sb, ext4_group_t grp, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:4087
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff81525a80-ffffffff81525e45: count_overhead (STB_LOCAL)
ffffffff81e806b3-ffffffff81e80781: count_overhead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int count_overhead(struct super_block *sb, ext4_group_t grp, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:4075
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff815c31a0-ffffffff815c356e: count_overhead (STB_LOCAL)
ffffffff820709db-ffffffff82070aa9: count_overhead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int count_overhead(struct super_block *sb, ext4_group_t grp, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:4126
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff815fa8f0-ffffffff815facbe: count_overhead (STB_LOCAL)
ffffffff820f0664-ffffffff820f0732: count_overhead.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int count_overhead(struct super_block *sb, ext4_group_t grp, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (0)
Location: fs/ext4/super.c:4132
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
**Symbols:**

```
ffffffff816334d0-ffffffff8163389e: count_overhead (STB_LOCAL)
ffffffff821cd837-ffffffff821cd905: count_overhead.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bded8)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c068169c)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f41c8)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000339990)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813dcf48)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cd9c8)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813da3e8)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ef6c8)
Location: fs/ext4/super.c:3460
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_calculate_overhead
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
