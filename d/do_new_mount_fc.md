# Function: <code>do_new_mount_fc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f4cf4)
Location: fs/namespace.c:2725
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff813068a6)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_new_mount_fc(struct fs_context *fc, struct path *mountpoint, unsigned int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133f0f0)
Location: fs/namespace.c:2802
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8133f0f0-ffffffff8133f222: do_new_mount_fc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_new_mount_fc(struct fs_context *fc, struct path *mountpoint, unsigned int mnt_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134b150)
Location: fs/namespace.c:2808
Inline: False
Direct callers:
  - fs/namespace.c:do_new_mount
```
**Symbols:**

```
ffffffff8134b150-ffffffff8134b282: do_new_mount_fc (STB_LOCAL)
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
In fs/namespace.c (ffffffff81351b78)
Location: fs/namespace.c:2841
Inline: True
Inline callers:
  - fs/namespace.c:do_new_mount
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
In fs/namespace.c (ffffffff8139fee8)
Location: fs/namespace.c:2915
Inline: True
Inline callers:
  - fs/namespace.c:do_new_mount
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
In fs/namespace.c (ffffffff81423539)
Location: fs/namespace.c:2958
Inline: True
Inline callers:
  - fs/namespace.c:do_new_mount
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
In fs/namespace.c (ffffffff814afc89)
Location: fs/namespace.c:3063
Inline: True
Inline callers:
  - fs/namespace.c:do_new_mount
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
In fs/namespace.c (ffffffff814e4cc0)
Location: fs/namespace.c:3253
Inline: True
Inline callers:
  - fs/namespace.c:do_new_mount
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
In fs/namespace.c (ffffffff81518aee)
Location: fs/namespace.c:3264
Inline: True
Inline callers:
  - fs/namespace.c:do_new_mount
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
In fs/namespace.c (ffff8000103b9ca4)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (c0597988)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (c0000000004b7568)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffe00027bf50)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812fee86)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812efaa6)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812fcc76)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff8130dfda)
Location: fs/namespace.c:2756
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
