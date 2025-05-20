# Function: <code>fuse_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130f250)
Location: fs/fuse/dev.c:1803
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8130f250-ffffffff8130fa5c: fuse_notify (STB_LOCAL)
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
In fs/fuse/dev.c (ffffffff81343a7f)
Location: fs/fuse/dev.c:1776
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813593b0)
Location: fs/fuse/dev.c:1750
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff813593b0-ffffffff81359bcd: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136dbc0)
Location: fs/fuse/dev.c:1755
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8136dbc0-ffffffff8136e397: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81392790)
Location: fs/fuse/dev.c:1755
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81392790-ffffffff81392fa3: fuse_notify (STB_LOCAL)
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
In fs/fuse/dev.c (ffffffff813c2604)
Location: fs/fuse/dev.c:1761
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
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
In fs/fuse/dev.c (ffffffff813dbfb5)
Location: fs/fuse/dev.c:1820
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81406ca0)
Location: fs/fuse/dev.c:1844
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81406ca0-ffffffff8140752a: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81421a80)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81421a80-ffffffff8142235a: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81470f30)
Location: fs/fuse/dev.c:1750
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81470f30-ffffffff8147141c: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148b800)
Location: fs/fuse/dev.c:1761
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8148b800-ffffffff8148bca2: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814907d0)
Location: fs/fuse/dev.c:1767
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff814907d0-ffffffff81490c72: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e8260)
Location: fs/fuse/dev.c:1783
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff814e8260-ffffffff814e8702: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81577280)
Location: fs/fuse/dev.c:1775
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81577280-ffffffff815777ca: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161c780)
Location: fs/fuse/dev.c:1776
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8161c780-ffffffff8161ccd1: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816548e0)
Location: fs/fuse/dev.c:1778
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff816548e0-ffffffff81654e3b: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168d8e0)
Location: fs/fuse/dev.c:1778
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8168d8e0-ffffffff8168dba9: fuse_notify (STB_LOCAL)
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
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffff800010504848)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffff800010504848-ffff80001050504c: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c06c0e4c)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
c06c0e4c-c06c1470: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (c000000000649970)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
c000000000649970-c00000000064a3f4: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffe0003713c2)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffe0003713c2-ffffffe000371ab0: fuse_notify (STB_LOCAL)
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
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8141a060)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8141a060-ffffffff8141a93a: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8140aae0)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8140aae0-ffffffff8140b3ba: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81416200)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff81416200-ffffffff81416ada: fuse_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fuse_notify(struct fuse_conn *fc, enum fuse_notify_code code, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8142cf60)
Location: fs/fuse/dev.c:1751
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
**Symbols:**

```
ffffffff8142cf60-ffffffff8142d83a: fuse_notify (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
