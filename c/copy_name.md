# Function: <code>copy_name</code>

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
In fs/dcache.c (ffffffff812248d6)
Location: fs/dcache.c:2511
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8124cc33)
Location: fs/dcache.c:2681
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8125fc23)
Location: fs/dcache.c:2690
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8126d58a)
Location: fs/dcache.c:2720
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8128fea7)
Location: fs/dcache.c:2730
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812b570c)
Location: fs/dcache.c:2750
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812caa2c)
Location: fs/dcache.c:2704
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812e744c)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812f8fbb)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff81331f7a)
Location: fs/dcache.c:2795
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8133d99a)
Location: fs/dcache.c:2802
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff81343c99)
Location: fs/dcache.c:2829
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff813915c9)
Location: fs/dcache.c:2830
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8141356a)
Location: fs/dcache.c:2855
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void copy_name(struct dentry *dentry, struct dentry *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2910
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff8149c840-ffffffff8149c930: copy_name (STB_LOCAL)
ffffffff820688f5-ffffffff82068912: copy_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void copy_name(struct dentry *dentry, struct dentry *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2910
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff814d1bd0-ffffffff814d1cc3: copy_name (STB_LOCAL)
ffffffff820e820e-ffffffff820e822b: copy_name.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void copy_name(struct dentry *dentry, struct dentry *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2734
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff815045a0-ffffffff81504693: copy_name (STB_LOCAL)
ffffffff821c4f4b-ffffffff821c4f68: copy_name.cold (STB_LOCAL)
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
In fs/dcache.c (ffff8000103a8350)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (c05890c8)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (c0000000004a1b88)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffe00026dabe)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812f159b)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812e21cb)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812ef3ab)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff813006bc)
Location: fs/dcache.c:2774
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
