# Function: <code>__mnt_drop_write_file</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8122d720)
Location: fs/namespace.c:483
Inline: False
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff8122d720-ffffffff8122d737: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81255ef0)
Location: fs/namespace.c:483
Inline: False
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff81255ef0-ffffffff81255f07: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812692e0)
Location: fs/namespace.c:482
Inline: False
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff812692e0-ffffffff812692f7: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81276a80)
Location: fs/namespace.c:483
Inline: False
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff81276a80-ffffffff81276a97: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81299490)
Location: fs/namespace.c:537
Inline: False
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff81299490-ffffffff812994a7: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bf310)
Location: fs/namespace.c:537
Inline: True
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff812bf310-ffffffff812bf327: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d2995)
Location: fs/namespace.c:454
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff812d4530-ffffffff812d4547: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812efb65)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff812f1a40-ffffffff812f1a57: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81301635)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff813035f0-ffffffff81303607: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133a715)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff8133d320-ffffffff8133d337: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81346a65)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff81349270-ffffffff81349287: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134cd45)
Location: fs/namespace.c:457
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff8134fc60-ffffffff8134fc7d: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139acb5)
Location: fs/namespace.c:459
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff8139dfa0-ffffffff8139dfbd: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8141e6e5)
Location: fs/namespace.c:475
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff814210b0-ffffffff814210f3: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aadf5)
Location: fs/namespace.c:590
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_modified_flags
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff814ad710-ffffffff814ad753: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814dfca5)
Location: fs/namespace.c:485
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_modified_flags
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff814e24f0-ffffffff814e2536: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b4a78)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffff8000103b6b50-ffff8000103b6b9c: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0592c1c)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
c05951b0-c05951f0: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b0ea0)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
c0000000004b3400-c0000000004b345c: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe000277586)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffe0002796e0-ffffffe00027972c: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f9c15)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff812fbbd0-ffffffff812fbbe7: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ea835)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff812ec7f0-ffffffff812ec807: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f7a05)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff812f99c0-ffffffff812f99d7: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __mnt_drop_write_file(struct file *file);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81308d35)
Location: fs/namespace.c:451
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
Direct callers:
  - fs/inode.c:file_update_time
```
**Symbols:**

```
ffffffff8130acd0-ffffffff8130acfd: __mnt_drop_write_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
