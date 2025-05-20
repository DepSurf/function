# Function: <code>mknod_ptmx</code>

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
In fs/devpts/inode.c (ffffffff8128de75)
Location: fs/devpts/inode.c:241
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
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
In fs/devpts/inode.c (ffffffff812bb48d)
Location: fs/devpts/inode.c:266
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_mount
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
In fs/devpts/inode.c (ffffffff812d0c69)
Location: fs/devpts/inode.c:266
Inline: True
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
In fs/devpts/inode.c (ffffffff812e2238)
Location: fs/devpts/inode.c:299
Inline: True
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
In fs/devpts/inode.c (ffffffff81306c18)
Location: fs/devpts/inode.c:327
Inline: True
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
In fs/devpts/inode.c (ffffffff81334c1b)
Location: fs/devpts/inode.c:327
Inline: True
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
In fs/devpts/inode.c (ffffffff8134bf66)
Location: fs/devpts/inode.c:325
Inline: True
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
In fs/devpts/inode.c (ffffffff81374930)
Location: fs/devpts/inode.c:322
Inline: True
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
In fs/devpts/inode.c (ffffffff8138cbb0)
Location: fs/devpts/inode.c:322
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mknod_ptmx(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:322
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
```
**Symbols:**

```
ffffffff813d7e40-ffffffff813d7f5e: mknod_ptmx (STB_LOCAL)
ffffffff813d8622-ffffffff813d8658: mknod_ptmx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mknod_ptmx(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:322
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
```
**Symbols:**

```
ffffffff813e9ae0-ffffffff813e9bfe: mknod_ptmx (STB_LOCAL)
ffffffff81bec1c6-ffffffff81bec1fc: mknod_ptmx.cold (STB_LOCAL)
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
In fs/devpts/inode.c (ffffffff813f0790)
Location: fs/devpts/inode.c:322
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
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
In fs/devpts/inode.c (ffffffff81442680)
Location: fs/devpts/inode.c:322
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
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
In fs/devpts/inode.c (ffffffff814be412)
Location: fs/devpts/inode.c:322
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
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
In fs/devpts/inode.c (ffffffff815561f2)
Location: fs/devpts/inode.c:322
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
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
In fs/devpts/inode.c (ffffffff8158dfa2)
Location: fs/devpts/inode.c:304
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
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
In fs/devpts/inode.c (ffffffff815c6cf0)
Location: fs/devpts/inode.c:303
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
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
In fs/devpts/inode.c (ffff80001045e768)
Location: fs/devpts/inode.c:322
Inline: True
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
In fs/devpts/inode.c (c061f1f8)
Location: fs/devpts/inode.c:322
Inline: True
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
In fs/devpts/inode.c (c00000000057a7a0)
Location: fs/devpts/inode.c:322
Inline: True
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
In fs/devpts/inode.c (ffffffe0002ee430)
Location: fs/devpts/inode.c:322
Inline: True
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
In fs/devpts/inode.c (ffffffff81385190)
Location: fs/devpts/inode.c:322
Inline: True
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
In fs/devpts/inode.c (ffffffff81375c20)
Location: fs/devpts/inode.c:322
Inline: True
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
In fs/devpts/inode.c (ffffffff81382c60)
Location: fs/devpts/inode.c:322
Inline: True
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
In fs/devpts/inode.c (ffffffff81396780)
Location: fs/devpts/inode.c:322
Inline: True
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
