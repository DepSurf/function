# Function: <code>iomap_dio_inline_actor</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8132412b)
Location: fs/iomap.c:1746
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (ffffffff8134dc01)
Location: fs/iomap/direct-io.c:337
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (ffffffff81365ec1)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
loff_t iomap_dio_inline_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813ad8b0)
Location: fs/iomap/direct-io.c:345
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff813ad8b0-ffffffff813ad9e0: iomap_dio_inline_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
loff_t iomap_dio_inline_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813beef0)
Location: fs/iomap/direct-io.c:347
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff813beef0-ffffffff813bf020: iomap_dio_inline_actor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
loff_t iomap_dio_inline_actor(struct inode *inode, loff_t pos, loff_t length, struct iomap_dio *dio, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813c6030)
Location: fs/iomap/direct-io.c:377
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff813c6030-ffffffff813c6160: iomap_dio_inline_actor (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/iomap/direct-io.c (ffff80001042cd6c)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (c05f5b24)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (c00000000053e518)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (ffffffe0002ca10a)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (ffffffff8135e4a1)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (ffffffff8134f141)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (ffffffff8135bf71)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
In fs/iomap/direct-io.c (ffffffff8136f6c1)
Location: fs/iomap/direct-io.c:335
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_actor
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
</ul>
