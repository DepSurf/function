# Function: <code>fanotify_fh_equal</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8136a61c)
Location: fs/notify/fanotify/fanotify.c:31
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
**Symbols:**

```
ffffffff8136a540-ffffffff8136a58e: fanotify_fh_equal.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8137787e)
Location: fs/notify/fanotify/fanotify.c:31
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
**Symbols:**

```
ffffffff81377690-ffffffff813776e3: fanotify_fh_equal.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8137e15d)
Location: fs/notify/fanotify/fanotify.c:44
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
**Symbols:**

```
ffffffff8137e010-ffffffff8137e063: fanotify_fh_equal.part.0 (STB_LOCAL)
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
In fs/notify/fanotify/fanotify.c (ffffffff813cb11e)
Location: fs/notify/fanotify/fanotify.c:44
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_merge
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_merge
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
**Symbols:**

```
ffffffff813caf50-ffffffff813cafa3: fanotify_fh_equal.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fanotify_fh_equal(struct fanotify_fh *fh1, struct fanotify_fh *fh2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81452b60)
Location: fs/notify/fanotify/fanotify.c:44
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
**Symbols:**

```
ffffffff81452b60-ffffffff81452bd5: fanotify_fh_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fanotify_fh_equal(struct fanotify_fh *fh1, struct fanotify_fh *fh2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814e1830)
Location: fs/notify/fanotify/fanotify.c:44
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
**Symbols:**

```
ffffffff814e1830-ffffffff814e18a5: fanotify_fh_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fanotify_fh_equal(struct fanotify_fh *fh1, struct fanotify_fh *fh2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff815180f0)
Location: fs/notify/fanotify/fanotify.c:44
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
**Symbols:**

```
ffffffff815180f0-ffffffff81518165: fanotify_fh_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fanotify_fh_equal(struct fanotify_fh *fh1, struct fanotify_fh *fh2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8154c4d0)
Location: fs/notify/fanotify/fanotify.c:38
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
  - fs/notify/fanotify/fanotify.c:fanotify_info_equal
```
**Symbols:**

```
ffffffff8154c4d0-ffffffff8154c545: fanotify_fh_equal (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
