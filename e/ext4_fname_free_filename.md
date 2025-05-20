# Function: <code>ext4_fname_free_filename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ext4_fname_free_filename(struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto_fname.c (ffffffff812e6ac0)
Location: fs/ext4/crypto_fname.c:464
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812e6ac0-ffffffff812e6af0: ext4_fname_free_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_free_filename(struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812d2ddb)
Location: fs/ext4/ext4.h:2320
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812d07d0-ffffffff812d0839: ext4_fname_free_filename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_free_filename(struct ext4_filename *fname);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff812e8b2b)
Location: fs/ext4/ext4.h:2300
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_find_entry
Direct callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
```
**Symbols:**

```
ffffffff812e6570-ffffffff812e65d9: ext4_fname_free_filename (STB_LOCAL)
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
In fs/ext4/namei.c (ffffffff8131aa9f)
Location: fs/ext4/ext4.h:2336
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff8133f1df)
Location: fs/ext4/ext4.h:2296
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff8136d120)
Location: fs/ext4/ext4.h:2297
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813855a0)
Location: fs/ext4/ext4.h:2310
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813af577)
Location: fs/ext4/ext4.h:2367
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813c84cf)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81414374)
Location: fs/ext4/ext4.h:2523
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142797c)
Location: fs/ext4/ext4.h:2655
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff8142e5f0)
Location: fs/ext4/ext4.h:2707
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff81482529)
Location: fs/ext4/ext4.h:2777
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_fname_free_filename(struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8153cc10)
Location: fs/ext4/crypto.c:58
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff8153cc10-ffffffff8153cc5a: ext4_fname_free_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_fname_free_filename(struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff815db3c0)
Location: fs/ext4/crypto.c:58
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff815db3c0-ffffffff815db40a: ext4_fname_free_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_fname_free_filename(struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff81612e70)
Location: fs/ext4/crypto.c:58
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff81612e70-ffffffff81612eba: ext4_fname_free_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ext4_fname_free_filename(struct ext4_filename *fname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8164bc19)
Location: fs/ext4/crypto.c:62
Inline: True
Inline callers:
  - fs/ext4/crypto.c:ext4_fname_prepare_lookup
  - fs/ext4/crypto.c:ext4_fname_setup_filename
Direct callers:
  - fs/ext4/namei.c:ext4_find_delete_entry
  - fs/ext4/namei.c:__ext4_unlink
  - fs/ext4/namei.c:ext4_rmdir
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff8164bc70-ffffffff8164bcba: ext4_fname_free_filename (STB_GLOBAL)
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
In fs/ext4/namei.c (ffff80001049fe80)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (c0661aa8)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (c0000000005cbeb4)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffe000322370)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813c0aaf)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813b153f)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813bdf59)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
In fs/ext4/namei.c (ffffffff813d303f)
Location: fs/ext4/ext4.h:2425
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_add_entry
  - fs/ext4/namei.c:ext4_find_entry
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
