# Function: <code>userfaultfd_ctx_read</code>

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
In fs/userfaultfd.c (ffffffff81259b82)
Location: fs/userfaultfd.c:542
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff8128259d)
Location: fs/userfaultfd.c:546
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff812960bd)
Location: fs/userfaultfd.c:581
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff812a3408)
Location: fs/userfaultfd.c:965
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff812c6985)
Location: fs/userfaultfd.c:1009
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff812f0da6)
Location: fs/userfaultfd.c:1014
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff813044b5)
Location: fs/userfaultfd.c:1019
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff8132633f)
Location: fs/userfaultfd.c:1035
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff813390cf)
Location: fs/userfaultfd.c:1035
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81373bf0)
Location: fs/userfaultfd.c:1034
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff81373bf0-ffffffff8137409b: userfaultfd_ctx_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81381b60)
Location: fs/userfaultfd.c:998
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff81381b60-ffffffff8138205f: userfaultfd_ctx_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81388bc0)
Location: fs/userfaultfd.c:998
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff81388bc0-ffffffff813890cd: userfaultfd_ctx_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff813d5ee0)
Location: fs/userfaultfd.c:994
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff813d5ee0-ffffffff813d63c2: userfaultfd_ctx_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8145dbc0)
Location: fs/userfaultfd.c:1003
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff8145dbc0-ffffffff8145e0ba: userfaultfd_ctx_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff814ed620)
Location: fs/userfaultfd.c:1023
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff814ed620-ffffffff814edb0e: userfaultfd_ctx_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff81524630)
Location: fs/userfaultfd.c:1052
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff81524630-ffffffff81524b22: userfaultfd_ctx_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (ffffffff8155b120)
Location: fs/userfaultfd.c:1045
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
ffffffff8155b120-ffffffff8155b612: userfaultfd_ctx_read (STB_LOCAL)
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
In fs/userfaultfd.c (ffff8000103f70f8)
Location: fs/userfaultfd.c:1035
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c05cb684)
Location: fs/userfaultfd.c:1035
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
c05cb684-c05cbb24: userfaultfd_ctx_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t userfaultfd_ctx_read(struct userfaultfd_ctx *ctx, int no_wait, struct uffd_msg *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/userfaultfd.c (c000000000500bf0)
Location: fs/userfaultfd.c:1035
Inline: False
Direct callers:
  - fs/userfaultfd.c:userfaultfd_read
```
**Symbols:**

```
c000000000500bf0-c0000000005012c0: userfaultfd_ctx_read (STB_LOCAL)
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
In fs/userfaultfd.c (ffffffe0002a7ce6)
Location: fs/userfaultfd.c:1035
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff813316af)
Location: fs/userfaultfd.c:1035
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff8132228f)
Location: fs/userfaultfd.c:1035
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff8132f17f)
Location: fs/userfaultfd.c:1035
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
In fs/userfaultfd.c (ffffffff813412b4)
Location: fs/userfaultfd.c:1035
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_read
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
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
