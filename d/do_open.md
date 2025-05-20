# Function: <code>do_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct file *do_open(struct path *path, int oflag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8132cc10)
Location: ipc/mqueue.c:758
Inline: True
Direct callers:
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff8132cc10-ffffffff8132cc7c: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct file *do_open(struct path *path, int oflag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81361870)
Location: ipc/mqueue.c:756
Inline: True
Direct callers:
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81361870-ffffffff813618dc: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct file *do_open(struct path *path, int oflag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff81378070)
Location: ipc/mqueue.c:756
Inline: True
Direct callers:
  - ipc/mqueue.c:SyS_mq_open
```
**Symbols:**

```
ffffffff81378070-ffffffff813780dc: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct file *do_open(struct path *path, int oflag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138ba80)
Location: ipc/mqueue.c:758
Inline: True
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8138ba80-ffffffff8138baec: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct file *do_open(struct path *path, int oflag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b0e20)
Location: ipc/mqueue.c:758
Inline: True
Direct callers:
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff813b0e20-ffffffff813b0e8c: do_open (STB_LOCAL)
```
</details>
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
int do_open(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813238e0)
Location: fs/namei.c:3201
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813238e0-ffffffff81323c15: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_open(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132eee0)
Location: fs/namei.c:3203
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8132eee0-ffffffff8132f215: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_open(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813366e0)
Location: fs/namei.c:3317
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813366e0-ffffffff81336aa4: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_open(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813840c0)
Location: fs/namei.c:3384
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff813840c0-ffffffff81384484: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_open(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814051c0)
Location: fs/namei.c:3478
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff814051c0-ffffffff8140566e: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_open(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148f610)
Location: fs/namei.c:3513
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff8148f610-ffffffff8148fad5: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_open(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c1e00)
Location: fs/namei.c:3592
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff814c1e00-ffffffff814c2266: do_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_open(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f42c0)
Location: fs/namei.c:3601
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff814f42c0-ffffffff814f4726: do_open (STB_LOCAL)
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
