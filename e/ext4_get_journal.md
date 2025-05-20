# Function: <code>ext4_get_journal</code>

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
In fs/ext4/super.c (ffffffff813228ce)
Location: fs/ext4/super.c:4085
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
In fs/ext4/super.c (ffffffff812eccad)
Location: fs/ext4/super.c:4247
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
In fs/ext4/super.c (ffffffff81302a9e)
Location: fs/ext4/super.c:4392
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
In fs/ext4/super.c (ffffffff81338439)
Location: fs/ext4/super.c:4500
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
In fs/ext4/super.c (ffffffff8135cef8)
Location: fs/ext4/super.c:4509
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
In fs/ext4/super.c (ffffffff81386698)
Location: fs/ext4/super.c:4620
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
In fs/ext4/super.c (ffffffff8139f198)
Location: fs/ext4/super.c:4683
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff813c96cd)
Location: fs/ext4/super.c:4773
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff813e29cd)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
journal_t *ext4_get_journal(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8142e410)
Location: fs/ext4/super.c:4965
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff8142e410-ffffffff8142e4ab: ext4_get_journal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
journal_t *ext4_get_journal(struct super_block *sb, unsigned int journal_inum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff814470f0)
Location: fs/ext4/super.c:5251
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_load_journal
```
**Symbols:**

```
ffffffff814470f0-ffffffff8144718b: ext4_get_journal (STB_LOCAL)
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
In fs/ext4/super.c (ffffffff8144de43)
Location: fs/ext4/super.c:5297
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff814a1ed4)
Location: fs/ext4/super.c:5152
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff81529150)
Location: fs/ext4/super.c:5598
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff815c7280)
Location: fs/ext4/super.c:5750
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff815ff30c)
Location: fs/ext4/super.c:5816
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffff8000104bbed4)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (c067f610)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (c0000000005f7174)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffe00033be20)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
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
In fs/ext4/super.c (ffffffff813dafad)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff813cba2d)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff813d844d)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
In fs/ext4/super.c (ffffffff813ed6ed)
Location: fs/ext4/super.c:4804
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
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
