# Function: <code>__revise_pending</code>

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
In fs/ext4/extents_status.c (ffffffff8135ab86)
Location: fs/ext4/extents_status.c:1720
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (ffffffff81383b99)
Location: fs/ext4/extents_status.c:1719
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (ffffffff8139c664)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __revise_pending(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e7100)
Location: fs/ext4/extents_status.c:2110
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff813e7100-ffffffff813e72c8: __revise_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __revise_pending(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f93c0)
Location: fs/ext4/extents_status.c:2134
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff813f93c0-ffffffff813f9588: __revise_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __revise_pending(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813fed90)
Location: fs/ext4/extents_status.c:2132
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff813fed90-ffffffff813fef5a: __revise_pending (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __revise_pending(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2132
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff814515c0-ffffffff814517c3: __revise_pending (STB_LOCAL)
ffffffff81cc9bf8-ffffffff81cc9c57: __revise_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __revise_pending(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2132
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff814cf6d0-ffffffff814cf942: __revise_pending (STB_LOCAL)
ffffffff81e7c8f2-ffffffff81e7c941: __revise_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __revise_pending(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2129
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff81567fa0-ffffffff81568212: __revise_pending (STB_LOCAL)
ffffffff8206cf1e-ffffffff8206cf6d: __revise_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __revise_pending(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2176
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff8159fba0-ffffffff8159fdba: __revise_pending (STB_LOCAL)
ffffffff820ecca6-ffffffff820ecd03: __revise_pending.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __revise_pending(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len, struct pending_reservation **prealloc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2238
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
```
**Symbols:**

```
ffffffff815d87d0-ffffffff815d8a66: __revise_pending (STB_LOCAL)
ffffffff821c9ee2-ffffffff821c9f2e: __revise_pending.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffff80001046f4d4)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (c0630a28)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (c00000000058f900)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (ffffffe0002fc066)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (ffffffff81394c44)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (ffffffff813856d4)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (ffffffff813925a4)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
In fs/ext4/extents_status.c (ffffffff813a64ea)
Location: fs/ext4/extents_status.c:2110
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_insert_extent
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pending_reservation **prealloc</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
</ul>
