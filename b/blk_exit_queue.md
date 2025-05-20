# Function: <code>blk_exit_queue</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_exit_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81482c30)
Location: block/blk-core.c:719
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff81482c30-ffffffff81482c74: blk_exit_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_exit_queue(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149e710)
Location: block/blk-core.c:294
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-sysfs.c:__blk_release_queue
```
**Symbols:**

```
ffffffff8149e710-ffffffff8149e751: blk_exit_queue (STB_GLOBAL)
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
In block/blk-sysfs.c (ffffffff814ce306)
Location: block/blk-sysfs.c:844
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (ffffffff814e7616)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (ffffffff81546536)
Location: block/blk-sysfs.c:848
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (ffffffff81562189)
Location: block/blk-sysfs.c:733
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
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
In block/blk-sysfs.c (ffffffff8156a8e9)
Location: block/blk-sysfs.c:751
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
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
In block/blk-sysfs.c (ffffffff815cedae)
Location: block/blk-sysfs.c:755
Inline: True
Inline callers:
  - block/blk-sysfs.c:blk_release_queue
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In block/blk-sysfs.c (ffff8000105e5164)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (c079216c)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (c000000000779088)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (ffffffe00042654a)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (ffffffff814dfbf6)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (ffffffff814d0596)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (ffffffff814dbc86)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
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
In block/blk-sysfs.c (ffffffff814f4af6)
Location: block/blk-sysfs.c:843
Inline: True
Inline callers:
  - block/blk-sysfs.c:__blk_release_queue
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
