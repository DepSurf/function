# Function: <code>fuse_request_queue_background</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool fuse_request_queue_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dd5e0)
Location: fs/fuse/dev.c:632
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff813dd5e0-ffffffff813dd6f5: fuse_request_queue_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool fuse_request_queue_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fuse/dev.c (0)
Location: fs/fuse/dev.c:656
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_send_writepage
```
**Symbols:**

```
ffffffff8140957b-ffffffff8140958e: fuse_request_queue_background.cold (STB_LOCAL)
ffffffff81409110-ffffffff81409230: fuse_request_queue_background (STB_GLOBAL)
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
In fs/fuse/dev.c (ffffffff8141fdb9)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool fuse_request_queue_background(struct fuse_conn *fc, struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146e280)
Location: fs/fuse/dev.c:514
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
```
**Symbols:**

```
ffffffff8146e280-ffffffff8146e3a7: fuse_request_queue_background (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fuse_request_queue_background(struct fuse_req *req);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81488a10)
Location: fs/fuse/dev.c:526
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_simple_background
```
**Symbols:**

```
ffffffff81488a10-ffffffff81488b29: fuse_request_queue_background (STB_LOCAL)
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
In fs/fuse/dev.c (ffffffff8148e90a)
Location: fs/fuse/dev.c:526
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff814e637a)
Location: fs/fuse/dev.c:526
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff81574eff)
Location: fs/fuse/dev.c:522
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff8161aa02)
Location: fs/fuse/dev.c:522
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff816523ed)
Location: fs/fuse/dev.c:524
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff8168b9fd)
Location: fs/fuse/dev.c:524
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffff80001050268c)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (c06bed3c)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (c000000000646e20)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffe00036f6d4)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff81418399)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff81408e19)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff81414539)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
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
In fs/fuse/dev.c (ffffffff8142b839)
Location: fs/fuse/dev.c:514
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_simple_background
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct fuse_conn *fc</code>
</li>
<li>
<b>Param reordered. </b>
<code>fc, req</code> ➡️ <code>req</code>
</li>
</ul>
</details>
</li>
</ul>
