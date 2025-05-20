# Function: <code>jbd2_write_access_granted</code>

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
In fs/jbd2/transaction.c (ffffffff812e73c0)
Location: fs/jbd2/transaction.c:1012
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
```
**Symbols:**

```
ffffffff812e73c0-ffffffff812e73ff: jbd2_write_access_granted.part.8 (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff81316595)
Location: fs/jbd2/transaction.c:1003
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81314f20-ffffffff81314f5f: jbd2_write_access_granted.part.8 (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff8132c585)
Location: fs/jbd2/transaction.c:1005
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8132af20-ffffffff8132af5f: jbd2_write_access_granted.part.9 (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff81341785)
Location: fs/jbd2/transaction.c:1018
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81340150-ffffffff8134018d: jbd2_write_access_granted.part.9 (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff81365db5)
Location: fs/jbd2/transaction.c:1021
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81364760-ffffffff813647a0: jbd2_write_access_granted.part.9 (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff813944d5)
Location: fs/jbd2/transaction.c:1017
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81392ed0-ffffffff81392f10: jbd2_write_access_granted.part.10 (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff813ad225)
Location: fs/jbd2/transaction.c:1050
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813abbf0-ffffffff813abc30: jbd2_write_access_granted.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d6020)
Location: fs/jbd2/transaction.c:1050
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813d6020-ffffffff813d6074: jbd2_write_access_granted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f0050)
Location: fs/jbd2/transaction.c:1051
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813f0050-ffffffff813f00aa: jbd2_write_access_granted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143c890)
Location: fs/jbd2/transaction.c:1130
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8143c890-ffffffff8143c8ea: jbd2_write_access_granted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145ac63)
Location: fs/jbd2/transaction.c:1132
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81458a60-ffffffff81458ae1: jbd2_write_access_granted.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814605a3)
Location: fs/jbd2/transaction.c:1137
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8145e3e0-ffffffff8145e461: jbd2_write_access_granted.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b5a23)
Location: fs/jbd2/transaction.c:1154
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff814b3910-ffffffff814b3991: jbd2_write_access_granted.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153f307)
Location: fs/jbd2/transaction.c:1163
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8153d190-ffffffff8153d24b: jbd2_write_access_granted.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815db850)
Location: fs/jbd2/transaction.c:1171
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff815db850-ffffffff815db8f2: jbd2_write_access_granted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81613310)
Location: fs/jbd2/transaction.c:1171
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81613310-ffffffff816133b2: jbd2_write_access_granted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164c110)
Location: fs/jbd2/transaction.c:1167
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8164c110-ffffffff8164c1b2: jbd2_write_access_granted (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffff8000104cb598)
Location: fs/jbd2/transaction.c:1051
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffff8000104c89c8-ffff8000104c8a64: jbd2_write_access_granted.isra.0.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (c068ef3c)
Location: fs/jbd2/transaction.c:1051
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
c068c918-c068c9a4: jbd2_write_access_granted.part.0 (STB_LOCAL)
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
In fs/jbd2/transaction.c (c00000000060475c)
Location: fs/jbd2/transaction.c:1051
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
c000000000602980-c000000000602a08: jbd2_write_access_granted.isra.0.part.0 (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffe000344402)
Location: fs/jbd2/transaction.c:1051
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffe000342c3c-ffffffe000342cac: jbd2_write_access_granted.isra.0.part.0 (STB_LOCAL)
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
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e8630)
Location: fs/jbd2/transaction.c:1051
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813e8630-ffffffff813e868a: jbd2_write_access_granted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d90b0)
Location: fs/jbd2/transaction.c:1051
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813d90b0-ffffffff813d910a: jbd2_write_access_granted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool jbd2_write_access_granted(handle_t *handle, struct buffer_head *bh, bool undo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e59b0)
Location: fs/jbd2/transaction.c:1051
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813e59b0-ffffffff813e5a0a: jbd2_write_access_granted (STB_LOCAL)
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
In fs/jbd2/transaction.c (ffffffff813fc547)
Location: fs/jbd2/transaction.c:1051
Inline: True
Inline callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813faed0-ffffffff813faf4f: jbd2_write_access_granted.part.0 (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
</ul>
