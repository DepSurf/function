# Function: <code>ext4_dio_write_checks</code>

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
ssize_t ext4_dio_write_checks(struct kiocb *iocb, struct iov_iter *from, bool *ilock_shared, bool *extend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813e9340)
Location: fs/ext4/file.c:405
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff813e9340-ffffffff813e9507: ext4_dio_write_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ext4_dio_write_checks(struct kiocb *iocb, struct iov_iter *from, bool *ilock_shared, bool *extend);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/file.c (ffffffff813fb700)
Location: fs/ext4/file.c:406
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff813fb700-ffffffff813fb8be: ext4_dio_write_checks (STB_LOCAL)
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
In fs/ext4/file.c (ffffffff8140209c)
Location: fs/ext4/file.c:422
Inline: True
Inline callers:
  - fs/ext4/file.c:ext4_dio_write_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:422
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff81454150-ffffffff8145432e: ext4_dio_write_checks.constprop.0 (STB_LOCAL)
ffffffff81cc9ce6-ffffffff81cc9e46: ext4_dio_write_checks.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:422
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff814d1860-ffffffff814d1a5f: ext4_dio_write_checks.constprop.0 (STB_LOCAL)
ffffffff81e7c9d2-ffffffff81e7cb3d: ext4_dio_write_checks.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:437
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff8156a0b0-ffffffff8156a2af: ext4_dio_write_checks.constprop.0 (STB_LOCAL)
ffffffff8206cffe-ffffffff8206d169: ext4_dio_write_checks.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:451
Inline: True
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff815a1eb0-ffffffff815a2201: ext4_dio_write_checks.constprop.0 (STB_LOCAL)
ffffffff820ecd7e-ffffffff820ecf93: ext4_dio_write_checks.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t ext4_dio_write_checks(struct kiocb *iocb, struct iov_iter *from, bool *ilock_shared, bool *extend, bool *unwritten, int *dio_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/file.c (0)
Location: fs/ext4/file.c:421
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_write_iter
```
**Symbols:**

```
ffffffff815dac00-ffffffff815daf36: ext4_dio_write_checks (STB_LOCAL)
ffffffff821c9f4c-ffffffff821ca0ee: ext4_dio_write_checks.cold (STB_LOCAL)
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
</ul>
