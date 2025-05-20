# Function: <code>do_get_write_access</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e8480)
Location: fs/jbd2/transaction.c:811
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
```
**Symbols:**

```
ffffffff812e8480-ffffffff812e8906: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813160d0)
Location: fs/jbd2/transaction.c:808
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813160d0-ffffffff81316510: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132c0c0)
Location: fs/jbd2/transaction.c:810
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8132c0c0-ffffffff8132c4fd: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813412c0)
Location: fs/jbd2/transaction.c:823
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813412c0-ffffffff813416f4: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813658f0)
Location: fs/jbd2/transaction.c:826
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813658f0-ffffffff81365d28: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:822
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81394060-ffffffff81394456: do_get_write_access (STB_LOCAL)
ffffffff8139529c-ffffffff813952f0: do_get_write_access.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:855
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813acdb0-ffffffff813ad1a6: do_get_write_access (STB_LOCAL)
ffffffff813ae00b-ffffffff813ae05f: do_get_write_access.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:855
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813d7020-ffffffff813d7453: do_get_write_access (STB_LOCAL)
ffffffff813d8462-ffffffff813d84ae: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813f1110-ffffffff813f14ea: do_get_write_access (STB_LOCAL)
ffffffff813f245d-ffffffff813f24a9: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:937
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8143e5d0-ffffffff8143e92c: do_get_write_access (STB_LOCAL)
ffffffff8143f820-ffffffff8143f839: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:939
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8145a870-ffffffff8145ab84: do_get_write_access (STB_LOCAL)
ffffffff81becbc4-ffffffff81becbdd: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:944
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81460100-ffffffff814604cc: do_get_write_access (STB_LOCAL)
ffffffff81bdec49-ffffffff81bdec9d: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:961
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff814b5580-ffffffff814b594f: do_get_write_access (STB_LOCAL)
ffffffff81cce48d-ffffffff81cce4e1: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:970
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8153eef0-ffffffff8153f216: do_get_write_access (STB_LOCAL)
ffffffff81e81519-ffffffff81e81532: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dd8f0)
Location: fs/jbd2/transaction.c:970
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff815dd8f0-ffffffff815ddc25: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81615370)
Location: fs/jbd2/transaction.c:970
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff81615370-ffffffff816156a9: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164e160)
Location: fs/jbd2/transaction.c:966
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff8164e160-ffffffff8164e496: do_get_write_access (STB_LOCAL)
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
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104caf80)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffff8000104caf80-ffff8000104cb488: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068e920)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
c068e920-c068ee40: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000603ff0)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
c000000000603ff0-c0000000006045d4: do_get_write_access (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe000343f06)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffe000343f06-ffffffe000344334: do_get_write_access (STB_LOCAL)
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
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813e96f0-ffffffff813e9aca: do_get_write_access (STB_LOCAL)
ffffffff813eaa3d-ffffffff813eaa89: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813da170-ffffffff813da54a: do_get_write_access (STB_LOCAL)
ffffffff813db4bd-ffffffff813db509: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813e6a70-ffffffff813e6e4a: do_get_write_access (STB_LOCAL)
ffffffff813e7dbd-ffffffff813e7e09: do_get_write_access.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_get_write_access(handle_t *handle, struct journal_head *jh, int force_copy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/transaction.c (0)
Location: fs/jbd2/transaction.c:858
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:jbd2_journal_get_write_access
```
**Symbols:**

```
ffffffff813fc000-ffffffff813fc474: do_get_write_access (STB_LOCAL)
ffffffff813fd5dc-ffffffff813fd628: do_get_write_access.cold (STB_LOCAL)
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
