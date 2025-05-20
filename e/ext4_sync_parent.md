# Function: <code>ext4_sync_parent</code>

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
In fs/ext4/fsync.c (ffffffff81292cfb)
Location: fs/ext4/fsync.c:44
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff812c021c)
Location: fs/ext4/fsync.c:44
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff812d5885)
Location: fs/ext4/fsync.c:44
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff812f35d3)
Location: fs/ext4/fsync.c:44
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff81317b6d)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff813459f5)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff8135db69)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff81386d03)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff8139f753)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_sync_parent(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff813eb350)
Location: fs/ext4/fsync.c:45
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
**Symbols:**

```
ffffffff813eb350-ffffffff813eb3ff: ext4_sync_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_sync_parent(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fsync.c (ffffffff813fd580)
Location: fs/ext4/fsync.c:45
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
**Symbols:**

```
ffffffff813fd580-ffffffff813fd62f: ext4_sync_parent (STB_LOCAL)
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
In fs/ext4/fsync.c (ffffffff81403bf0)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff8145646a)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff814d3ee0)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff8156cb5b)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff815a49a7)
Location: fs/ext4/fsync.c:46
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff815dd7e6)
Location: fs/ext4/fsync.c:46
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffff800010472a90)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (c0633f2c)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (c000000000593960)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffe0002fe8ac)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff81397d33)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff813887c3)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff81395693)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
In fs/ext4/fsync.c (ffffffff813a97e0)
Location: fs/ext4/fsync.c:45
Inline: True
Inline callers:
  - fs/ext4/fsync.c:ext4_sync_file
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
