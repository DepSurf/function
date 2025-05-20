# Function: <code>write_inode</code>

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
In fs/fs-writeback.c (ffffffff8123b1c3)
Location: fs/fs-writeback.c:1122
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff8126307d)
Location: fs/fs-writeback.c:1159
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff812764cd)
Location: fs/fs-writeback.c:1159
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff81283958)
Location: fs/fs-writeback.c:1173
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff812a64f1)
Location: fs/fs-writeback.c:1176
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff812cd0b0)
Location: fs/fs-writeback.c:1177
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff812e23d0)
Location: fs/fs-writeback.c:1203
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff81300de4)
Location: fs/fs-writeback.c:1218
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff813134b4)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134bb30)
Location: fs/fs-writeback.c:1316
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
**Symbols:**

```
ffffffff8134bb30-ffffffff8134bc22: write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81358a60)
Location: fs/fs-writeback.c:1314
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
**Symbols:**

```
ffffffff81358a60-ffffffff81358b25: write_inode (STB_LOCAL)
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
In fs/fs-writeback.c (ffffffff81360935)
Location: fs/fs-writeback.c:1320
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff813aefaf)
Location: fs/fs-writeback.c:1463
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814334f0)
Location: fs/fs-writeback.c:1434
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
**Symbols:**

```
ffffffff814334f0-ffffffff814335e8: write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c1130)
Location: fs/fs-writeback.c:1445
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
**Symbols:**

```
ffffffff814c1130-ffffffff814c1224: write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f5f60)
Location: fs/fs-writeback.c:1450
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
**Symbols:**

```
ffffffff814f5f60-ffffffff814f6054: write_inode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int write_inode(struct inode *inode, struct writeback_control *wbc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152a670)
Location: fs/fs-writeback.c:1467
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
**Symbols:**

```
ffffffff8152a670-ffffffff8152a764: write_inode (STB_LOCAL)
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
In fs/fs-writeback.c (ffff8000103c8cf0)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (c05a562c)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (c0000000004ca350)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffe00028740c)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff8130ba94)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff812fc6b4)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff81309884)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
In fs/fs-writeback.c (ffffffff8131a269)
Location: fs/fs-writeback.c:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
