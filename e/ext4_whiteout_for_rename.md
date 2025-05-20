# Function: <code>ext4_whiteout_for_rename</code>

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
In fs/ext4/namei.c (ffffffff812a77f1)
Location: fs/ext4/namei.c:3432
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff812d689e)
Location: fs/ext4/namei.c:3461
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff812ec59e)
Location: fs/ext4/namei.c:3463
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff8131c2b0)
Location: fs/ext4/namei.c:3451
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff8134089c)
Location: fs/ext4/namei.c:3447
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff8136e850)
Location: fs/ext4/namei.c:3419
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff81386ce0)
Location: fs/ext4/namei.c:3422
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff813b0cc1)
Location: fs/ext4/namei.c:3589
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff813c9cea)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct inode *ext4_whiteout_for_rename(struct ext4_renament *ent, int credits, handle_t **h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8140fbe0)
Location: fs/ext4/namei.c:3639
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff8140fbe0-ffffffff8140fcfe: ext4_whiteout_for_rename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct inode *ext4_whiteout_for_rename(struct ext4_renament *ent, int credits, handle_t **h);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81423270)
Location: fs/ext4/namei.c:3689
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81423270-ffffffff81423393: ext4_whiteout_for_rename (STB_LOCAL)
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
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3819
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3649
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3706
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3723
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3746
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (0)
Location: fs/ext4/namei.c:3754
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffff8000104a1890)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (c0663a28)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (c0000000005ce3a4)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffe00032380c)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff813c22ca)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff813b2d5a)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff813bf77a)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
In fs/ext4/namei.c (ffffffff813d485a)
Location: fs/ext4/namei.c:3600
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename
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
