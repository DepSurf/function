# Function: <code>ext4_dx_csum_verify</code>

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
In fs/ext4/namei.c (ffffffff812a1f00)
Location: fs/ext4/namei.c:436
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff812d0e57)
Location: fs/ext4/namei.c:435
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff812e6bd7)
Location: fs/ext4/namei.c:435
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff81316735)
Location: fs/ext4/namei.c:435
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff8133afa5)
Location: fs/ext4/namei.c:436
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff813695ed)
Location: fs/ext4/namei.c:437
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff81381a83)
Location: fs/ext4/namei.c:438
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff813aac21)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff813c3b51)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_dx_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff814100b0)
Location: fs/ext4/namei.c:460
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff814100b0-ffffffff814101d0: ext4_dx_csum_verify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_dx_csum_verify(struct inode *inode, struct ext4_dir_entry *dirent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81423580)
Location: fs/ext4/namei.c:456
Inline: False
Direct callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
```
**Symbols:**

```
ffffffff81423580-ffffffff814236a0: ext4_dx_csum_verify (STB_LOCAL)
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
In fs/ext4/namei.c (ffffffff81429f7f)
Location: fs/ext4/namei.c:458
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff8147df4f)
Location: fs/ext4/namei.c:459
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff81500caf)
Location: fs/ext4/namei.c:482
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff8159b7fb)
Location: fs/ext4/namei.c:487
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff815d2078)
Location: fs/ext4/namei.c:487
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff8160a808)
Location: fs/ext4/namei.c:489
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffff80001049b62c)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (c065d18c)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (c0000000005c6228)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffe00031eae2)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff813bc131)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff813acbc1)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff813b9b11)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
In fs/ext4/namei.c (ffffffff813ce6b1)
Location: fs/ext4/namei.c:453
Inline: True
Inline callers:
  - fs/ext4/namei.c:__ext4_read_dirblock
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
