# Function: <code>ext4_xattr_update_super_block</code>

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
In fs/ext4/xattr.c (ffffffff812de6fc)
Location: fs/ext4/xattr.c:524
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff8130e39d)
Location: fs/ext4/xattr.c:549
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff81324119)
Location: fs/ext4/xattr.c:554
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff8133de19)
Location: fs/ext4/xattr.c:750
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff813623f1)
Location: fs/ext4/xattr.c:760
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff81390bd8)
Location: fs/ext4/xattr.c:789
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff813a97b8)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff813d3c6d)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff813ed34d)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff8143a3fc)
Location: fs/ext4/xattr.c:787
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_xattr_update_super_block(handle_t *handle, struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144f7d0)
Location: fs/ext4/xattr.c:787
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
**Symbols:**

```
ffffffff8144f7d0-ffffffff8144f893: ext4_xattr_update_super_block (STB_LOCAL)
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
In fs/ext4/xattr.c (ffffffff81458726)
Location: fs/ext4/xattr.c:787
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff814ac82d)
Location: fs/ext4/xattr.c:787
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff81534740)
Location: fs/ext4/xattr.c:802
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff815d2c60)
Location: fs/ext4/xattr.c:818
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff8160a772)
Location: fs/ext4/xattr.c:846
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff81643529)
Location: fs/ext4/xattr.c:846
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffff8000104c60ec)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (c068a0c0)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (c0000000005fe5b8)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffe00034067a)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff813e592d)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff813d63ad)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff813e2cad)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
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
In fs/ext4/xattr.c (ffffffff813f80bd)
Location: fs/ext4/xattr.c:785
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_set_handle
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
