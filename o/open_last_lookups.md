# Function: <code>open_last_lookups</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *open_last_lookups(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81325ef0)
Location: fs/namei.c:3111
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81325ef0-ffffffff81326303: open_last_lookups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *open_last_lookups(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81331390)
Location: fs/namei.c:3117
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81331390-ffffffff813317a2: open_last_lookups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *open_last_lookups(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81337d50)
Location: fs/namei.c:3231
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81337d50-ffffffff81338162: open_last_lookups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *open_last_lookups(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813857e0)
Location: fs/namei.c:3298
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813857e0-ffffffff81385bc5: open_last_lookups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *open_last_lookups(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814065d0)
Location: fs/namei.c:3392
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff814065d0-ffffffff81406a2b: open_last_lookups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *open_last_lookups(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81490950)
Location: fs/namei.c:3429
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff81490950-ffffffff81490d61: open_last_lookups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *open_last_lookups(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c6180)
Location: fs/namei.c:3508
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff814c6180-ffffffff814c6571: open_last_lookups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *open_last_lookups(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f8a70)
Location: fs/namei.c:3516
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff814f8a70-ffffffff814f8e68: open_last_lookups (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
