# Function: <code>ext4_clear_journal_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff812ba2c0)
Location: fs/ext4/super.c:4418
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_remount
```
**Symbols:**

```
ffffffff812ba2c0-ffffffff812ba3a9: ext4_clear_journal_err.isra.195 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff812e91e0)
Location: fs/ext4/super.c:4582
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812e91e0-ffffffff812e92c9: ext4_clear_journal_err.isra.196 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff812fef20)
Location: fs/ext4/super.c:4708
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff812fef20-ffffffff812ff009: ext4_clear_journal_err.isra.198 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff81333cd0)
Location: fs/ext4/super.c:4816
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffff81333cd0-ffffffff81333db9: ext4_clear_journal_err.isra.203 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813581e0)
Location: fs/ext4/super.c:4825
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813581e0-ffffffff813582c9: ext4_clear_journal_err.isra.204 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff81386360)
Location: fs/ext4/super.c:4940
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81386360-ffffffff81386452: ext4_clear_journal_err.isra.130 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff8139ee60)
Location: fs/ext4/super.c:5004
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8139ee60-ffffffff8139ef52: ext4_clear_journal_err.isra.134 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813c94e0)
Location: fs/ext4/super.c:5094
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813c94e0-ffffffff813c95d1: ext4_clear_journal_err.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813e27e0)
Location: fs/ext4/super.c:5125
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813e27e0-ffffffff813e28d1: ext4_clear_journal_err.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142f700)
Location: fs/ext4/super.c:5308
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8142f700-ffffffff8142f817: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81448430)
Location: fs/ext4/super.c:5634
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81448430-ffffffff81448544: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8144dc80)
Location: fs/ext4/super.c:5682
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8144dc80-ffffffff8144dd94: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814a1d10)
Location: fs/ext4/super.c:5544
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff814a1d10-ffffffff814a1e24: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81528f70)
Location: fs/ext4/super.c:6000
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81528f70-ffffffff815290a7: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815c7090)
Location: fs/ext4/super.c:6152
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff815c7090-ffffffff815c71c7: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff815fee10)
Location: fs/ext4/super.c:6239
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff815fee10-ffffffff815fef4f: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81637a10)
Location: fs/ext4/super.c:6267
Inline: False
Direct callers:
  - fs/ext4/super.c:__ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff81637a10-ffffffff81637b4f: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffff8000104bbc18)
Location: fs/ext4/super.c:5125
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffff8000104bbc18-ffff8000104bbd30: ext4_clear_journal_err.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ext4_clear_journal_err(struct super_block *sb, struct ext4_super_block *es);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (c067f37c)
Location: fs/ext4/super.c:5125
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
c067f37c-c067f484: ext4_clear_journal_err (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (c0000000005f1c40)
Location: fs/ext4/super.c:5125
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
c0000000005f1c40-c0000000005f1d80: ext4_clear_journal_err.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffe000337ecc)
Location: fs/ext4/super.c:5125
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_fill_super
```
**Symbols:**

```
ffffffe000337ecc-ffffffe000337fb4: ext4_clear_journal_err.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813dadc0)
Location: fs/ext4/super.c:5125
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813dadc0-ffffffff813daeb1: ext4_clear_journal_err.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813cb840)
Location: fs/ext4/super.c:5125
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813cb840-ffffffff813cb931: ext4_clear_journal_err.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813d8260)
Location: fs/ext4/super.c:5125
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813d8260-ffffffff813d8351: ext4_clear_journal_err.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/super.c (ffffffff813ed500)
Location: fs/ext4/super.c:5125
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_remount
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff813ed500-ffffffff813ed5f1: ext4_clear_journal_err.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
