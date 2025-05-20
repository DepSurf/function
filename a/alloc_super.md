# Function: <code>alloc_super</code>

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
In fs/super.c (ffffffff8120f56d)
Location: fs/super.c:184
Inline: True
Inline callers:
  - fs/super.c:sget_userns
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
In fs/super.c (ffffffff81235fb1)
Location: fs/super.c:184
Inline: True
Inline callers:
  - fs/super.c:sget_userns
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
In fs/super.c (ffffffff81248c87)
Location: fs/super.c:184
Inline: True
Inline callers:
  - fs/super.c:sget_userns
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
In fs/super.c (ffffffff81254592)
Location: fs/super.c:183
Inline: True
Inline callers:
  - fs/super.c:sget_userns
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
In fs/super.c (ffffffff81276712)
Location: fs/super.c:182
Inline: True
Inline callers:
  - fs/super.c:sget_userns
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
In fs/super.c (ffffffff8129d128)
Location: fs/super.c:194
Inline: True
Inline callers:
  - fs/super.c:sget_userns
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
In fs/super.c (ffffffff812b20d8)
Location: fs/super.c:198
Inline: True
Inline callers:
  - fs/super.c:sget_userns
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cdfc0)
Location: fs/super.c:199
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff812cdfc0-ffffffff812ce26a: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812dfa10)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff812dfa10-ffffffff812dfcd8: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81316970)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81316970-ffffffff81316c62: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81321e30)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81321e30-ffffffff81322164: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81327f00)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff81327f00-ffffffff81328230: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813754d0)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff813754d0-ffffffff81375800: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f4880)
Location: fs/super.c:199
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff813f4880-ffffffff813f4b81: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147d990)
Location: fs/super.c:199
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff8147d990-ffffffff8147dc9b: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b2730)
Location: fs/super.c:199
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff814b2730-ffffffff814b2a21: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e50d0)
Location: fs/super.c:314
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff814e50d0-ffffffff814e5456: alloc_super (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff8000103864b8)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffff8000103864b8-ffff80001038674c: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056ff10)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
c056ff10-c05701a0: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047dd20)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
c00000000047dd20-c00000000047e04c: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000258f86)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffe000258f86-ffffffe0002591f0: alloc_super (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7ff0)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff812d7ff0-ffffffff812d82b8: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c8c70)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff812c8c70-ffffffff812c8f38: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d5e00)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff812d5e00-ffffffff812d60c8: alloc_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct super_block *alloc_super(struct file_system_type *type, int flags, struct user_namespace *user_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e7760)
Location: fs/super.c:200
Inline: False
Direct callers:
  - fs/super.c:sget
  - fs/super.c:sget_fc
```
**Symbols:**

```
ffffffff812e7760-ffffffff812e7a28: alloc_super (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
