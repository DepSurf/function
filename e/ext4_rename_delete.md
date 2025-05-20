# Function: <code>ext4_rename_delete</code>

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
In fs/ext4/namei.c (ffffffff812a7d4a)
Location: fs/ext4/namei.c:3389
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
In fs/ext4/namei.c (ffffffff812d6e1f)
Location: fs/ext4/namei.c:3418
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
In fs/ext4/namei.c (ffffffff812ecb02)
Location: fs/ext4/namei.c:3420
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
In fs/ext4/namei.c (ffffffff8131c741)
Location: fs/ext4/namei.c:3408
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
In fs/ext4/namei.c (ffffffff81340cfe)
Location: fs/ext4/namei.c:3404
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
In fs/ext4/namei.c (ffffffff8136ecf6)
Location: fs/ext4/namei.c:3376
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
In fs/ext4/namei.c (ffffffff81387186)
Location: fs/ext4/namei.c:3379
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
In fs/ext4/namei.c (ffffffff813b1132)
Location: fs/ext4/namei.c:3546
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
In fs/ext4/namei.c (ffffffff813ca167)
Location: fs/ext4/namei.c:3557
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
void ext4_rename_delete(handle_t *handle, struct ext4_renament *ent, int force_reread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814148b0)
Location: fs/ext4/namei.c:3596
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff814148b0-ffffffff81414a24: ext4_rename_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_rename_delete(handle_t *handle, struct ext4_renament *ent, int force_reread);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81427f00)
Location: fs/ext4/namei.c:3646
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_rename
```
**Symbols:**

```
ffffffff81427f00-ffffffff81428074: ext4_rename_delete (STB_LOCAL)
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
In fs/ext4/namei.c (ffffffff8142fe5f)
Location: fs/ext4/namei.c:3776
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
In fs/ext4/namei.c (ffffffff814844af)
Location: fs/ext4/namei.c:3606
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
In fs/ext4/namei.c (ffffffff8150766e)
Location: fs/ext4/namei.c:3663
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
In fs/ext4/namei.c (ffffffff815a217e)
Location: fs/ext4/namei.c:3680
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
In fs/ext4/namei.c (ffffffff815d8b1a)
Location: fs/ext4/namei.c:3703
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
In fs/ext4/namei.c (ffffffff816111dc)
Location: fs/ext4/namei.c:3711
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
In fs/ext4/namei.c (ffff8000104a1cbc)
Location: fs/ext4/namei.c:3557
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
In fs/ext4/namei.c (c0663eb0)
Location: fs/ext4/namei.c:3557
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
In fs/ext4/namei.c (c0000000005ce930)
Location: fs/ext4/namei.c:3557
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
In fs/ext4/namei.c (ffffffe000323bac)
Location: fs/ext4/namei.c:3557
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
In fs/ext4/namei.c (ffffffff813c2747)
Location: fs/ext4/namei.c:3557
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
In fs/ext4/namei.c (ffffffff813b31d7)
Location: fs/ext4/namei.c:3557
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
In fs/ext4/namei.c (ffffffff813bfbf7)
Location: fs/ext4/namei.c:3557
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
In fs/ext4/namei.c (ffffffff813d4cd7)
Location: fs/ext4/namei.c:3557
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
