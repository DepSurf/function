# Function: <code>umount_list</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff81285ff4)
Location: fs/pnode.c:488
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff812a8a74)
Location: fs/pnode.c:488
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff812cf66f)
Location: fs/pnode.c:488
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff812e49df)
Location: fs/pnode.c:489
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff813031cd)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff8131624d)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void umount_list(struct list_head *to_umount, struct list_head *to_restore);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8134f210)
Location: fs/pnode.c:481
Inline: False
Direct callers:
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff8134f210-ffffffff8134f34f: umount_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void umount_list(struct list_head *to_umount, struct list_head *to_restore);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pnode.c (ffffffff8135c0c0)
Location: fs/pnode.c:481
Inline: False
Direct callers:
  - fs/pnode.c:propagate_umount
```
**Symbols:**

```
ffffffff8135c0c0-ffffffff8135c1ff: umount_list (STB_LOCAL)
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
In fs/pnode.c (ffffffff81363405)
Location: fs/pnode.c:481
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff813b1c05)
Location: fs/pnode.c:481
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff81436be5)
Location: fs/pnode.c:481
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff814c4c45)
Location: fs/pnode.c:481
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff814fa0c2)
Location: fs/pnode.c:519
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff8152e91a)
Location: fs/pnode.c:519
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffff8000103ccbdc)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (c05a87d0)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (c0000000004ce294)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffe000289e32)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff8130e82d)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff812ff43d)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff8130c61d)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
In fs/pnode.c (ffffffff8131de4d)
Location: fs/pnode.c:482
Inline: True
Inline callers:
  - fs/pnode.c:propagate_umount
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
