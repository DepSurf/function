# Function: <code>ext4_valid_extent_entries</code>

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
In fs/ext4/extents.c (ffffffff812c2930)
Location: fs/ext4/extents.c:394
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff812f22f3)
Location: fs/ext4/extents.c:403
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813082c3)
Location: fs/ext4/extents.c:403
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff812e6abb)
Location: fs/ext4/extents.c:403
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff8130b46a)
Location: fs/ext4/extents.c:403
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813395f1)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff81350791)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813793e1)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff81391942)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813dd462)
Location: fs/ext4/extents.c:354
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813eed52)
Location: fs/ext4/extents.c:354
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff813f51f6)
Location: fs/ext4/extents.c:354
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_valid_extent_entries(struct inode *inode, struct ext4_extent_header *eh, ext4_lblk_t lblk, ext4_fsblk_t *pblk, int depth);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814477d0)
Location: fs/ext4/extents.c:368
Inline: False
Direct callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
**Symbols:**

```
ffffffff814477d0-ffffffff8144793f: ext4_valid_extent_entries (STB_LOCAL)
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
In fs/ext4/extents.c (ffffffff814c3e4e)
Location: fs/ext4/extents.c:368
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff8155c327)
Location: fs/ext4/extents.c:387
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff81594127)
Location: fs/ext4/extents.c:387
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff815cce17)
Location: fs/ext4/extents.c:387
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffff800010464510)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (c0624754)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (c0000000005814c8)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffe0002f2768)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff81389f22)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff8137a9b2)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff81387882)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
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
In fs/ext4/extents.c (ffffffff8139b562)
Location: fs/ext4/extents.c:391
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
