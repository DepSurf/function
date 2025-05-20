# Function: <code>fuse_read_single_forget</code>

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
In fs/fuse/dev.c (ffffffff8130e56b)
Location: fs/fuse/dev.c:1139
Inline: True
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
In fs/fuse/dev.c (ffffffff813428c4)
Location: fs/fuse/dev.c:1114
Inline: True
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
In fs/fuse/dev.c (ffffffff813586f4)
Location: fs/fuse/dev.c:1117
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
In fs/fuse/dev.c (ffffffff8136eaa0)
Location: fs/fuse/dev.c:1116
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
In fs/fuse/dev.c (ffffffff813936a4)
Location: fs/fuse/dev.c:1116
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
In fs/fuse/dev.c (ffffffff813c1d9a)
Location: fs/fuse/dev.c:1129
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
In fs/fuse/dev.c (ffffffff813db569)
Location: fs/fuse/dev.c:1182
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
In fs/fuse/dev.c (ffffffff814079c2)
Location: fs/fuse/dev.c:1206
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
In fs/fuse/dev.c (ffffffff8142138c)
Location: fs/fuse/dev.c:1074
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_read_single_forget(struct fuse_iqueue *fiq, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8146eaf0)
Location: fs/fuse/dev.c:1073
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
**Symbols:**

```
ffffffff8146eaf0-ffffffff8146ec75: fuse_read_single_forget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_read_single_forget(struct fuse_iqueue *fiq, struct fuse_copy_state *cs, size_t nbytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81489270)
Location: fs/fuse/dev.c:1094
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_read
```
**Symbols:**

```
ffffffff81489270-ffffffff814893f5: fuse_read_single_forget (STB_LOCAL)
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
In fs/fuse/dev.c (ffffffff8148f542)
Location: fs/fuse/dev.c:1091
Inline: True
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
In fs/fuse/dev.c (ffffffff814e6fb2)
Location: fs/fuse/dev.c:1107
Inline: True
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
In fs/fuse/dev.c (ffffffff81575854)
Location: fs/fuse/dev.c:1099
Inline: True
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
In fs/fuse/dev.c (ffffffff8161bb54)
Location: fs/fuse/dev.c:1100
Inline: True
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
In fs/fuse/dev.c (ffffffff81653cb7)
Location: fs/fuse/dev.c:1102
Inline: True
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
In fs/fuse/dev.c (ffffffff8168d2c7)
Location: fs/fuse/dev.c:1102
Inline: True
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
In fs/fuse/dev.c (ffff8000105040dc)
Location: fs/fuse/dev.c:1074
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
In fs/fuse/dev.c (c06c0734)
Location: fs/fuse/dev.c:1074
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
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
In fs/fuse/dev.c (c0000000006491e0)
Location: fs/fuse/dev.c:1074
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_read
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
In fs/fuse/dev.c (ffffffe000370e9c)
Location: fs/fuse/dev.c:1074
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
In fs/fuse/dev.c (ffffffff8141996c)
Location: fs/fuse/dev.c:1074
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
In fs/fuse/dev.c (ffffffff8140a3ec)
Location: fs/fuse/dev.c:1074
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
In fs/fuse/dev.c (ffffffff81415b0c)
Location: fs/fuse/dev.c:1074
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
In fs/fuse/dev.c (ffffffff8142c8b0)
Location: fs/fuse/dev.c:1074
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
