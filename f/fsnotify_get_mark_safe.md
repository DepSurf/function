# Function: <code>fsnotify_get_mark_safe</code>

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
bool fsnotify_get_mark_safe(struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299290)
Location: fs/notify/mark.c:117
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
**Symbols:**

```
ffffffff81299290-ffffffff812992d1: fsnotify_get_mark_safe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool fsnotify_get_mark_safe(struct fsnotify_mark *mark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bcb00)
Location: fs/notify/mark.c:257
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
**Symbols:**

```
ffffffff812bcb00-ffffffff812bcbbb: fsnotify_get_mark_safe (STB_LOCAL)
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
In fs/notify/mark.c (ffffffff812e5810)
Location: fs/notify/mark.c:257
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffff812fa3ff)
Location: fs/notify/mark.c:301
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffff8131adff)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffff8132d9ef)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367aef)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81374e6f)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffff8137b82f)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c85ec)
Location: fs/notify/mark.c:312
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144fbbc)
Location: fs/notify/mark.c:355
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814de4ec)
Location: fs/notify/mark.c:355
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81514d1c)
Location: fs/notify/mark.c:355
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815490fc)
Location: fs/notify/mark.c:355
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffff8000103ea02c)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (c05c1550)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (c0000000004f103c)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffe00029e8b4)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffff81325fcf)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffff81316b6f)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffff81323a9f)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
In fs/notify/mark.c (ffffffff813357df)
Location: fs/notify/mark.c:288
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_prepare_user_wait
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
</ul>
