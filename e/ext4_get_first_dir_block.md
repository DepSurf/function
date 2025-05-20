# Function: <code>ext4_get_first_dir_block</code>

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
In fs/ext4/namei.c (ffffffff812a2a89)
Location: fs/ext4/namei.c:3257
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff812d19c9)
Location: fs/ext4/namei.c:3286
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff812e7749)
Location: fs/ext4/namei.c:3288
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff813170c9)
Location: fs/ext4/namei.c:3276
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff8133b939)
Location: fs/ext4/namei.c:3272
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff8136a009)
Location: fs/ext4/namei.c:3244
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff813824c9)
Location: fs/ext4/namei.c:3247
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff813ab709)
Location: fs/ext4/namei.c:3413
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff813c4639)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff81410da9)
Location: fs/ext4/namei.c:3463
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff81424269)
Location: fs/ext4/namei.c:3491
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff8142ac79)
Location: fs/ext4/namei.c:3621
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff8147ec59)
Location: fs/ext4/namei.c:3449
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff81501970)
Location: fs/ext4/namei.c:3482
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
```
**Symbols:**

```
ffffffff81501970-ffffffff81501b1e: ext4_get_first_dir_block.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff8159c500)
Location: fs/ext4/namei.c:3499
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
```
**Symbols:**

```
ffffffff8159c500-ffffffff8159c6ae: ext4_get_first_dir_block.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff815d2d20)
Location: fs/ext4/namei.c:3521
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
```
**Symbols:**

```
ffffffff815d2d20-ffffffff815d2ed8: ext4_get_first_dir_block.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/namei.c (ffffffff8160b4b0)
Location: fs/ext4/namei.c:3523
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
```
**Symbols:**

```
ffffffff8160b4b0-ffffffff8160b668: ext4_get_first_dir_block.isra.0 (STB_LOCAL)
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
In fs/ext4/namei.c (ffff80001049c164)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (c065de84)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (c0000000005c6fe8)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffe00031f368)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff813bcc19)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff813ad6a9)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff813ba5f9)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
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
In fs/ext4/namei.c (ffffffff813cf199)
Location: fs/ext4/namei.c:3424
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_rename_dir_prepare
```
</details>
</li>
</ul>

## Differences
