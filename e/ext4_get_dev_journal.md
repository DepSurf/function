# Function: <code>ext4_get_dev_journal</code>

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
In fs/ext4/super.c (ffffffff8132299f)
Location: fs/ext4/super.c:4128
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff812eb67c)
Location: fs/ext4/super.c:4290
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813015f4)
Location: fs/ext4/super.c:4415
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff81338966)
Location: fs/ext4/super.c:4523
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff8135cf61)
Location: fs/ext4/super.c:4532
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff81386564)
Location: fs/ext4/super.c:4643
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff8139f064)
Location: fs/ext4/super.c:4706
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813c9040)
Location: fs/ext4/super.c:4796
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813c9040-ffffffff813c93ac: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813e23f0)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813e23f0-ffffffff813e275a: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142e4b0)
Location: fs/ext4/super.c:4989
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8142e4b0-ffffffff8142e81e: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81447190)
Location: fs/ext4/super.c:5275
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81447190-ffffffff814474e0: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144c990)
Location: fs/ext4/super.c:5321
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8144c990-ffffffff8144ccf1: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a0a20)
Location: fs/ext4/super.c:5176
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff814a0a20-ffffffff814a0d81: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815274e0)
Location: fs/ext4/super.c:5622
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff815274e0-ffffffff81527858: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c55c0)
Location: fs/ext4/super.c:5774
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff815c55c0-ffffffff815c5938: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fd1e0)
Location: fs/ext4/super.c:5841
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff815fd1e0-ffffffff815fd55a: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bb7e0)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffff8000104bb7e0-ffff8000104bbb50: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067ef40)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
c067ef40-c067f2c4: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c0000000005f16b0)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c0000000005f16b0-c0000000005f1b48: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffe000337b36)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe000337b36-ffffffe000337e46: ext4_get_dev_journal (STB_LOCAL)
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
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813da9d0)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813da9d0-ffffffff813dad3a: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813cb450)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813cb450-ffffffff813cb7ba: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813d7e70)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813d7e70-ffffffff813d81da: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
journal_t *ext4_get_dev_journal(struct super_block *sb, dev_t j_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff813ed110)
Location: fs/ext4/super.c:4827
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813ed110-ffffffff813ed472: ext4_get_dev_journal (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
