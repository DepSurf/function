# Function: <code>blk_integrity_compare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff813e7ef0)
Location: block/blk-integrity.c:143
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff813e7ef0-ffffffff813e8032: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff8142e190)
Location: block/blk-integrity.c:143
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff8142e190-ffffffff8142e2d0: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81447f30)
Location: block/blk-integrity.c:143
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81447f30-ffffffff81448070: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81456140)
Location: block/blk-integrity.c:143
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81456140-ffffffff8145627b: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81481da0)
Location: block/blk-integrity.c:143
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81481da0-ffffffff81481edb: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:143
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff814b74c1-ffffffff814b7548: blk_integrity_compare.cold.13 (STB_LOCAL)
ffffffff814b69f0-ffffffff814b6aad: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:135
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff814caca1-ffffffff814cad28: blk_integrity_compare.cold.13 (STB_LOCAL)
ffffffff814ca200-ffffffff814ca2bd: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff814f9593-ffffffff814f963d: blk_integrity_compare.cold (STB_LOCAL)
ffffffff814f8ad0-ffffffff814f8b72: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81517453-ffffffff815174fd: blk_integrity_compare.cold (STB_LOCAL)
ffffffff81516980-ffffffff81516a22: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81577bc5-ffffffff81577c6f: blk_integrity_compare.cold (STB_LOCAL)
ffffffff81577050-ffffffff815770f2: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81bf3cc0-ffffffff81bf3d6a: blk_integrity_compare.cold (STB_LOCAL)
ffffffff81593d00-ffffffff81593d9c: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81be5b22-ffffffff81be5bcc: blk_integrity_compare.cold (STB_LOCAL)
ffffffff8159aae0-ffffffff8159ab77: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81cda0f2-ffffffff81cda1e5: blk_integrity_compare.cold (STB_LOCAL)
ffffffff81602d00-ffffffff81602db1: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81e8dbd8-ffffffff81e8dcbf: blk_integrity_compare.cold (STB_LOCAL)
ffffffff816b5c20-ffffffff816b5cf6: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff820770c8-ffffffff82077117: blk_integrity_compare.cold (STB_LOCAL)
ffffffff81775610-ffffffff817757a2: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff820f7116-ffffffff820f7165: blk_integrity_compare.cold (STB_LOCAL)
ffffffff817b5260-ffffffff817b53f2: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff821d490b-ffffffff821d495a: blk_integrity_compare.cold (STB_LOCAL)
ffffffff817f9c70-ffffffff817f9e02: blk_integrity_compare (STB_GLOBAL)
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
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffff80001061dbd8)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffff80001061dbd8-ffff80001061dd10: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (c07c572c)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
c07c572c-c07c5894: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (c0000000007bcc20)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
c0000000007bcc20-c0000000007bcdc0: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffe000450a1c)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffe000450a1c-ffffffe000450b3a: blk_integrity_compare (STB_GLOBAL)
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
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff8150fa33-ffffffff8150fadd: blk_integrity_compare.cold (STB_LOCAL)
ffffffff8150ef60-ffffffff8150f002: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff814ffd53-ffffffff814ffdfd: blk_integrity_compare.cold (STB_LOCAL)
ffffffff814ff390-ffffffff814ff432: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff8150bac3-ffffffff8150bb6d: blk_integrity_compare.cold (STB_LOCAL)
ffffffff8150aff0-ffffffff8150b092: blk_integrity_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int blk_integrity_compare(struct gendisk *gd1, struct gendisk *gd2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-integrity.c (0)
Location: block/blk-integrity.c:121
Inline: False
Direct callers:
  - drivers/md/md.c:md_integrity_register
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-table.c:dm_table_get_integrity_disk
```
**Symbols:**

```
ffffffff81525163-ffffffff8152520d: blk_integrity_compare.cold (STB_LOCAL)
ffffffff81524690-ffffffff81524732: blk_integrity_compare (STB_GLOBAL)
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
