# Function: <code>ext4_mb_get_buddy_page_lock</code>

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
In fs/ext4/mballoc.c (ffffffff812cf474)
Location: fs/ext4/mballoc.c:985
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff812fee09)
Location: fs/ext4/mballoc.c:985
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff81314e79)
Location: fs/ext4/mballoc.c:985
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff8130c349)
Location: fs/ext4/mballoc.c:983
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff81330ea9)
Location: fs/ext4/mballoc.c:983
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff8135f474)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff81377914)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff813a0d84)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff813b9bea)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_mb_get_buddy_page_lock(struct super_block *sb, ext4_group_t group, struct ext4_buddy *e4b, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81403010)
Location: fs/ext4/mballoc.c:1033
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
**Symbols:**

```
ffffffff81403010-ffffffff8140311c: ext4_mb_get_buddy_page_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_mb_get_buddy_page_lock(struct super_block *sb, ext4_group_t group, struct ext4_buddy *e4b, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814158f0)
Location: fs/ext4/mballoc.c:1012
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
**Symbols:**

```
ffffffff814158f0-ffffffff814159fc: ext4_mb_get_buddy_page_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141f200)
Location: fs/ext4/mballoc.c:1346
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8147292a)
Location: fs/ext4/mballoc.c:1350
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff814f3913)
Location: fs/ext4/mballoc.c:1347
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff8158df03)
Location: fs/ext4/mballoc.c:1304
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff815c487c)
Location: fs/ext4/mballoc.c:1427
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff815fcb0c)
Location: fs/ext4/mballoc.c:1444
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffff800010490488)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (c06515cc)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (c0000000005b7984)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffe000315490)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff813b21ca)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff813a2c5a)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff813afa2a)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
In fs/ext4/mballoc.c (ffffffff813c4461)
Location: fs/ext4/mballoc.c:972
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init_group
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
</ul>
