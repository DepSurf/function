# Function: <code>fasync_insert_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121f7c0)
Location: fs/fcntl.c:623
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff8121f7c0-ffffffff8121f88e: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81247030)
Location: fs/fcntl.c:627
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff81247030-ffffffff812470fd: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8125a020)
Location: fs/fcntl.c:627
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff8125a020-ffffffff8125a0ed: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812669e0)
Location: fs/fcntl.c:897
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812669e0-ffffffff81266aaf: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81289280)
Location: fs/fcntl.c:907
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff81289280-ffffffff8128934f: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812af600)
Location: fs/fcntl.c:914
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812af600-ffffffff812af6c9: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c4780)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812c4780-ffffffff812c4849: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e11b0)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812e11b0-ffffffff812e1277: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f2c60)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812f2c60-ffffffff812f2d27: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8132aef0)
Location: fs/fcntl.c:920
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff8132aef0-ffffffff8132afba: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff813364c0)
Location: fs/fcntl.c:922
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff813364c0-ffffffff8133658a: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133c660)
Location: fs/fcntl.c:927
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff8133c660-ffffffff8133c72a: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8138a360)
Location: fs/fcntl.c:931
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff8138a360-ffffffff8138a42a: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8140b440)
Location: fs/fcntl.c:909
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff8140b440-ffffffff8140b50c: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81495d80)
Location: fs/fcntl.c:910
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff81495d80-ffffffff81495e4c: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814cadc0)
Location: fs/fcntl.c:911
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff814cadc0-ffffffff814cae8c: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fd670)
Location: fs/fcntl.c:912
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff814fd670-ffffffff814fd73c: fasync_insert_entry (STB_GLOBAL)
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
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039d1c0)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffff80001039d1c0-ffff80001039d364: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0582ad0)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
c0582ad0-c0582bc8: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000497f30)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
c000000000497f30-c0000000004980e4: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe00026930e)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffe00026930e-ffffffe000269434: fasync_insert_entry (STB_GLOBAL)
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
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812eb240)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812eb240-ffffffff812eb307: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dbe70)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812dbe70-ffffffff812dbf31: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e9050)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812e9050-ffffffff812e9117: fasync_insert_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fasync_struct *fasync_insert_entry(int fd, struct file *filp, struct fasync_struct **fapp, struct fasync_struct *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812fa050)
Location: fs/fcntl.c:918
Inline: False
Direct callers:
  - fs/fcntl.c:fasync_helper
  - fs/locks.c:lease_setup
```
**Symbols:**

```
ffffffff812fa050-ffffffff812fa112: fasync_insert_entry (STB_GLOBAL)
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
