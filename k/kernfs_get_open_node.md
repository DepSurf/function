# Function: <code>kernfs_get_open_node</code>

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
In fs/kernfs/file.c (ffffffff8128bcb0)
Location: fs/kernfs/file.c:538
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff812b916c)
Location: fs/kernfs/file.c:544
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff812ce8b9)
Location: fs/kernfs/file.c:544
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff812dbef6)
Location: fs/kernfs/file.c:543
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff81300816)
Location: fs/kernfs/file.c:543
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff8132e4b1)
Location: fs/kernfs/file.c:543
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff813458a1)
Location: fs/kernfs/file.c:543
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff8136d8de)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff81385c1e)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernfs_get_open_node(struct kernfs_node *kn, struct kernfs_open_file *of);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813d0580)
Location: fs/kernfs/file.c:542
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff813d0580-ffffffff813d0699: kernfs_get_open_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernfs_get_open_node(struct kernfs_node *kn, struct kernfs_open_file *of);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff813e2150)
Location: fs/kernfs/file.c:523
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff813e2150-ffffffff813e2269: kernfs_get_open_node (STB_LOCAL)
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
In fs/kernfs/file.c (0)
Location: fs/kernfs/file.c:523
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (0)
Location: fs/kernfs/file.c:523
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (0)
Location: fs/kernfs/file.c:517
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff8154d4f6)
Location: fs/kernfs/file.c:561
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff815850a6)
Location: fs/kernfs/file.c:561
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff815bdb25)
Location: fs/kernfs/file.c:512
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffff800010454fb8)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (0)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (c00000000056ec30)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffe0002e6fa0)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff8137e1fe)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff8136ecae)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff8137bcce)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
In fs/kernfs/file.c (ffffffff8138f7be)
Location: fs/kernfs/file.c:542
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_fop_open
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
