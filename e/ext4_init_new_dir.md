# Function: <code>ext4_init_new_dir</code>

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
In fs/ext4/namei.c (ffffffff812a6b46)
Location: fs/ext4/namei.c:2564
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff812d5ba9)
Location: fs/ext4/namei.c:2588
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff812eb8a9)
Location: fs/ext4/namei.c:2590
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff8131b5f1)
Location: fs/ext4/namei.c:2569
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff8133fc24)
Location: fs/ext4/namei.c:2564
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff8136dc32)
Location: fs/ext4/namei.c:2565
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff813860b2)
Location: fs/ext4/namei.c:2566
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff813b0121)
Location: fs/ext4/namei.c:2706
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff813c90e1)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff81414af0)
Location: fs/ext4/namei.c:2745
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
```
**Symbols:**

```
ffffffff81414af0-ffffffff81414c75: ext4_init_new_dir.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_init_new_dir(handle_t *handle, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81428140)
Location: fs/ext4/namei.c:2735
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
```
**Symbols:**

```
ffffffff81428140-ffffffff814282c5: ext4_init_new_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_init_new_dir(handle_t *handle, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8142ec40)
Location: fs/ext4/namei.c:2863
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
```
**Symbols:**

```
ffffffff8142ec40-ffffffff8142edcd: ext4_init_new_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_init_new_dir(handle_t *handle, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814833e0)
Location: fs/ext4/namei.c:2871
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
```
**Symbols:**

```
ffffffff814833e0-ffffffff8148356d: ext4_init_new_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_init_new_dir(handle_t *handle, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81506560)
Location: fs/ext4/namei.c:2921
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/fast_commit.c:ext4_fc_replay_create
```
**Symbols:**

```
ffffffff81506560-ffffffff815066e6: ext4_init_new_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_init_new_dir(handle_t *handle, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815a1030)
Location: fs/ext4/namei.c:2934
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815a1030-ffffffff815a11b6: ext4_init_new_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_init_new_dir(handle_t *handle, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d79b0)
Location: fs/ext4/namei.c:2955
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff815d79b0-ffffffff815d7b36: ext4_init_new_dir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_init_new_dir(handle_t *handle, struct inode *dir, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81610020)
Location: fs/ext4/namei.c:2956
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_mkdir
  - fs/ext4/fast_commit.c:ext4_fc_replay
```
**Symbols:**

```
ffffffff81610020-ffffffff816101a6: ext4_init_new_dir (STB_GLOBAL)
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
In fs/ext4/namei.c (ffff8000104a0b88)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (c0662e34)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (c0000000005cd1a8)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffe000322d18)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff813c16c1)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff813b2151)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff813beb71)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
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
In fs/ext4/namei.c (ffffffff813d3c51)
Location: fs/ext4/namei.c:2714
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_mkdir
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
