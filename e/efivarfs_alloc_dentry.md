# Function: <code>efivarfs_alloc_dentry</code>

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
In fs/efivarfs/super.c (ffffffff8132199d)
Location: fs/efivarfs/super.c:92
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff81356d6d)
Location: fs/efivarfs/super.c:91
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff8136d1cd)
Location: fs/efivarfs/super.c:91
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff81381726)
Location: fs/efivarfs/super.c:90
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff813a6736)
Location: fs/efivarfs/super.c:90
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff813d5a4e)
Location: fs/efivarfs/super.c:90
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff813f00af)
Location: fs/efivarfs/super.c:90
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff8141c3d4)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff81436224)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *efivarfs_alloc_dentry(struct dentry *parent, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff81485e10)
Location: fs/efivarfs/super.c:86
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff81485e10-ffffffff81485e88: efivarfs_alloc_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *efivarfs_alloc_dentry(struct dentry *parent, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/efivarfs/super.c (ffffffff814a3400)
Location: fs/efivarfs/super.c:86
Inline: False
Direct callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
**Symbols:**

```
ffffffff814a3400-ffffffff814a3478: efivarfs_alloc_dentry (STB_LOCAL)
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
In fs/efivarfs/super.c (ffffffff814a95e2)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff81501972)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff81592d74)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff8163a81e)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff81672dd5)
Location: fs/efivarfs/super.c:123
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff816af179)
Location: fs/efivarfs/super.c:167
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffff80001051c5c8)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (c06d8c38)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In fs/efivarfs/super.c (ffffffff8142e804)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff8141f284)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff8142a9a4)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
In fs/efivarfs/super.c (ffffffff81441864)
Location: fs/efivarfs/super.c:86
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_callback
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
