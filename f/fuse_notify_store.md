# Function: <code>fuse_notify_store</code>

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
In fs/fuse/dev.c (ffffffff8130f499)
Location: fs/fuse/dev.c:1606
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff81343d7b)
Location: fs/fuse/dev.c:1579
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
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
In fs/fuse/dev.c (ffffffff813595eb)
Location: fs/fuse/dev.c:1553
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff8136ddee)
Location: fs/fuse/dev.c:1558
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff813929c4)
Location: fs/fuse/dev.c:1558
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff813c2ab6)
Location: fs/fuse/dev.c:1564
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
In fs/fuse/dev.c (ffffffff813dc0e5)
Location: fs/fuse/dev.c:1621
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
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
In fs/fuse/dev.c (ffffffff81406f1c)
Location: fs/fuse/dev.c:1645
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff81421cfc)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fuse_notify_store(struct fuse_conn *fc, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81470c60)
Location: fs/fuse/dev.c:1533
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff81470c60-ffffffff81470f28: fuse_notify_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fuse_notify_store(struct fuse_conn *fc, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8148b540)
Location: fs/fuse/dev.c:1546
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8148b540-ffffffff8148b7f2: fuse_notify_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_notify_store(struct fuse_conn *fc, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81490510)
Location: fs/fuse/dev.c:1552
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff81490510-ffffffff814907cf: fuse_notify_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_notify_store(struct fuse_conn *fc, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff814e7fa0)
Location: fs/fuse/dev.c:1568
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff814e7fa0-ffffffff814e825c: fuse_notify_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_notify_store(struct fuse_conn *fc, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81576f60)
Location: fs/fuse/dev.c:1560
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff81576f60-ffffffff81577279: fuse_notify_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_notify_store(struct fuse_conn *fc, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8161b640)
Location: fs/fuse/dev.c:1561
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8161b640-ffffffff8161b959: fuse_notify_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_notify_store(struct fuse_conn *fc, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff816537b0)
Location: fs/fuse/dev.c:1563
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff816537b0-ffffffff81653ac0: fuse_notify_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_notify_store(struct fuse_conn *fc, unsigned int size, struct fuse_copy_state *cs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8168cdc0)
Location: fs/fuse/dev.c:1563
Inline: False
Direct callers:
  - fs/fuse/dev.c:fuse_notify
```
**Symbols:**

```
ffffffff8168cdc0-ffffffff8168d0cd: fuse_notify_store (STB_LOCAL)
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
In fs/fuse/dev.c (ffff800010504ab4)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (c06c1108)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (c000000000649cb0)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffe00037162e)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff8141a2dc)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff8140ad5c)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff8141647c)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
In fs/fuse/dev.c (ffffffff8142d1dc)
Location: fs/fuse/dev.c:1534
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_notify
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
