# Function: <code>ext4_wait_for_tail_page_commit</code>

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
In fs/ext4/inode.c (ffffffff8129eb87)
Location: fs/ext4/inode.c:4671
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff812cd10c)
Location: fs/ext4/inode.c:5010
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff812e2e88)
Location: fs/ext4/inode.c:5151
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff813073f8)
Location: fs/ext4/inode.c:5258
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff8132bfe1)
Location: fs/ext4/inode.c:5315
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff8135a5a7)
Location: fs/ext4/inode.c:5405
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff813728f2)
Location: fs/ext4/inode.c:5457
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff8139bd25)
Location: fs/ext4/inode.c:5470
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff813b4823)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff813ffcc1)
Location: fs/ext4/inode.c:5191
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff814124ca)
Location: fs/ext4/inode.c:5257
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff81418935)
Location: fs/ext4/inode.c:5252
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff8146bb2a)
Location: fs/ext4/inode.c:5192
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ext4_wait_for_tail_page_commit(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5272
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff814e0c30-ffffffff814e0dac: ext4_wait_for_tail_page_commit (STB_LOCAL)
ffffffff81e7d6b1-ffffffff81e7d6ec: ext4_wait_for_tail_page_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ext4_wait_for_tail_page_commit(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5373
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff8157a220-ffffffff8157a35a: ext4_wait_for_tail_page_commit (STB_LOCAL)
ffffffff8206dcd0-ffffffff8206dd0b: ext4_wait_for_tail_page_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ext4_wait_for_tail_page_commit(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5185
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff815b1db0-ffffffff815b1eed: ext4_wait_for_tail_page_commit (STB_LOCAL)
ffffffff820ed9f8-ffffffff820eda33: ext4_wait_for_tail_page_commit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ext4_wait_for_tail_page_commit(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:5206
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff815eabe0-ffffffff815ead18: ext4_wait_for_tail_page_commit (STB_LOCAL)
ffffffff821cab28-ffffffff821cab62: ext4_wait_for_tail_page_commit.cold (STB_LOCAL)
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
In fs/ext4/inode.c (ffff800010488f3c)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (c064b464)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (c0000000005afd04)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffe00031084a)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff813ace03)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff8139d893)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff813aa663)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
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
In fs/ext4/inode.c (ffffffff813bef78)
Location: fs/ext4/inode.c:5476
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_setattr
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
