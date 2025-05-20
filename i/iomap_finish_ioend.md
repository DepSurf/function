# Function: <code>iomap_finish_ioend</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void iomap_finish_ioend(struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1095
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
**Symbols:**

```
ffffffff813ab280-ffffffff813ab3ea: iomap_finish_ioend (STB_LOCAL)
ffffffff813acced-ffffffff813acd15: iomap_finish_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void iomap_finish_ioend(struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1064
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
**Symbols:**

```
ffffffff813bc7b0-ffffffff813bc919: iomap_finish_ioend (STB_LOCAL)
ffffffff81bebb27-ffffffff81bebb4f: iomap_finish_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void iomap_finish_ioend(struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1064
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
**Symbols:**

```
ffffffff813c2cd0-ffffffff813c2f15: iomap_finish_ioend (STB_LOCAL)
ffffffff81bddb86-ffffffff81bddbb2: iomap_finish_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void iomap_finish_ioend(struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1033
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
**Symbols:**

```
ffffffff81412360-ffffffff814125e2: iomap_finish_ioend (STB_LOCAL)
ffffffff81cc7727-ffffffff81cc7789: iomap_finish_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u32 iomap_finish_ioend(struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1030
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
**Symbols:**

```
ffffffff81488420-ffffffff81488a85: iomap_finish_ioend (STB_LOCAL)
ffffffff81e79d2b-ffffffff81e79e30: iomap_finish_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u32 iomap_finish_ioend(struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1291
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
**Symbols:**

```
ffffffff8151c2a0-ffffffff8151c74c: iomap_finish_ioend (STB_LOCAL)
ffffffff8206ac94-ffffffff8206ad6f: iomap_finish_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u32 iomap_finish_ioend(struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1311
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
**Symbols:**

```
ffffffff815544d0-ffffffff81554942: iomap_finish_ioend (STB_LOCAL)
ffffffff820eac2f-ffffffff820eacd3: iomap_finish_ioend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u32 iomap_finish_ioend(struct iomap_ioend *ioend, int error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/buffered-io.c (0)
Location: fs/iomap/buffered-io.c:1479
Inline: False
Direct callers:
  - fs/iomap/buffered-io.c:iomap_writepage_end_bio
  - fs/iomap/buffered-io.c:iomap_finish_ioends
  - fs/iomap/buffered-io.c:iomap_finish_ioends
```
**Symbols:**

```
ffffffff8158a6b0-ffffffff8158ab3f: iomap_finish_ioend (STB_LOCAL)
ffffffff821c7b6d-ffffffff821c7c20: iomap_finish_ioend.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
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
