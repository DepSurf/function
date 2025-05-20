# Function: <code>jbd2_journal_init_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f2140)
Location: fs/jbd2/journal.c:1187
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff812f2140-ffffffff812f2307: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131fa10)
Location: fs/jbd2/journal.c:1215
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff8131fa10-ffffffff8131fbcf: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81333cb0)
Location: fs/jbd2/journal.c:1215
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81333cb0-ffffffff81333d71: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81348a70)
Location: fs/jbd2/journal.c:1238
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81348a70-ffffffff81348b31: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136d0c0)
Location: fs/jbd2/journal.c:1254
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8136d0c0-ffffffff8136d181: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1251
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8139e2b0-ffffffff8139e2ca: jbd2_journal_init_inode.cold.47 (STB_LOCAL)
ffffffff8139b670-ffffffff8139b71a: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1251
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813b7020-ffffffff813b703a: jbd2_journal_init_inode.cold.48 (STB_LOCAL)
ffffffff813b4430-ffffffff813b44da: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1234
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813e173c-ffffffff813e1757: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff813dea40-ffffffff813deaed: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813fb7a2-ffffffff813fb7bd: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff813f8b00-ffffffff813f8bad: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1248
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_journal
```
**Symbols:**

```
ffffffff81448f05-ffffffff81448f20: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff81445b00-ffffffff81445c1f: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1429
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_journal
```
**Symbols:**

```
ffffffff81bed168-ffffffff81bed183: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff81463cf0-ffffffff81463e0f: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1429
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81bdf157-ffffffff81bdf172: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff814682f0-ffffffff8146840f: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1477
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81cceb3b-ffffffff81cceb84: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff814be970-ffffffff814bea9a: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1483
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81e81ad6-ffffffff81e81b1d: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff815497a0-ffffffff815498d9: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1488
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff82071438-ffffffff82071467: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff815e9850-ffffffff815e99a8: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1490
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff820f10fd-ffffffff820f112c: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff81621660-ffffffff816217a7: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1669
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff821ce32a-ffffffff821ce359: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff8165b1e0-ffffffff8165b343: jbd2_journal_init_inode (STB_GLOBAL)
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
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d4018)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffff8000104d4018-ffff8000104d40dc: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c06974cc)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
c06974cc-c06975b8: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c00000000060faf0)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c00000000060faf0-c00000000060fbe0: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034b7a8)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe00034b7a8-ffffffe00034b86a: jbd2_journal_init_inode (STB_GLOBAL)
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
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813f3d82-ffffffff813f3d9d: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff813f10e0-ffffffff813f118d: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813e4802-ffffffff813e481d: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff813e1b60-ffffffff813e1c0d: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813f1102-ffffffff813f111d: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff813ee460-ffffffff813ee50d: jbd2_journal_init_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
journal_t *jbd2_journal_init_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1233
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81406cfd-ffffffff81406d18: jbd2_journal_init_inode.cold (STB_LOCAL)
ffffffff814040b0-ffffffff8140415d: jbd2_journal_init_inode (STB_GLOBAL)
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
