# Function: <code>fsnotify_grab_connector</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(struct fsnotify_mark_connector **connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299470)
Location: fs/notify/mark.c:476
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81299470-ffffffff812994d8: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(struct fsnotify_mark_connector **connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bc7e0)
Location: fs/notify/mark.c:473
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff812bc7e0-ffffffff812bc848: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(struct fsnotify_mark_connector **connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5740)
Location: fs/notify/mark.c:480
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff812e5740-ffffffff812e57a8: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812f9ec0)
Location: fs/notify/mark.c:520
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff812f9ec0-ffffffff812f9f28: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131a6a0)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
ffffffff8131a6a0-ffffffff8131a72b: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d4e0)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff8132d4e0-ffffffff8132d56b: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367290)
Location: fs/notify/mark.c:520
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
ffffffff81367290-ffffffff8136731b: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813745f0)
Location: fs/notify/mark.c:520
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
ffffffff813745f0-ffffffff81374678: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137afa0)
Location: fs/notify/mark.c:518
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
ffffffff8137afa0-ffffffff8137b028: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c7c00)
Location: fs/notify/mark.c:547
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
ffffffff813c7c00-ffffffff813c7c88: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144f200)
Location: fs/notify/mark.c:582
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
```
**Symbols:**

```
ffffffff8144f200-ffffffff8144f282: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814dda40)
Location: fs/notify/mark.c:582
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
```
**Symbols:**

```
ffffffff814dda40-ffffffff814ddac2: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81514220)
Location: fs/notify/mark.c:582
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
```
**Symbols:**

```
ffffffff81514220-ffffffff815142a2: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815486f0)
Location: fs/notify/mark.c:574
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
```
**Symbols:**

```
ffffffff815486f0-ffffffff81548772: fsnotify_grab_connector (STB_LOCAL)
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
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e96c0)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
ffff8000103e96c0-ffff8000103e97a8: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c0e5c)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
c05c0e5c-c05c0f68: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004f06e0)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
c0000000004f06e0-c0000000004f0804: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029de62)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_list
```
**Symbols:**

```
ffffffe00029de62-ffffffe00029df36: fsnotify_grab_connector (STB_LOCAL)
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
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81325ac0)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81325ac0-ffffffff81325b4b: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316660)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81316660-ffffffff813166eb: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323590)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81323590-ffffffff8132361b: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fsnotify_mark_connector *fsnotify_grab_connector(fsnotify_connp_t *connp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81335600)
Location: fs/notify/mark.c:516
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_find_mark
  - fs/notify/mark.c:fsnotify_add_mark_locked
```
**Symbols:**

```
ffffffff81335600-ffffffff8133568b: fsnotify_grab_connector (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fsnotify_mark_connector **connp</code> ➡️ <code>fsnotify_connp_t *connp</code>
</li>
</ul>
</details>
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
