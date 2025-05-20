# Function: <code>fanotify_info_equal</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fanotify_info_equal(struct fanotify_info *info1, struct fanotify_info *info2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813776f0)
Location: fs/notify/fanotify/fanotify.c:52
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
**Symbols:**

```
ffffffff813776f0-ffffffff813777b5: fanotify_info_equal (STB_LOCAL)
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
In fs/notify/fanotify/fanotify.c (ffffffff8137e13d)
Location: fs/notify/fanotify/fanotify.c:75
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
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
In fs/notify/fanotify/fanotify.c (ffffffff813cb0f6)
Location: fs/notify/fanotify/fanotify.c:75
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool fanotify_info_equal(struct fanotify_info *info1, struct fanotify_info *info2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81453210)
Location: fs/notify/fanotify/fanotify.c:75
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
**Symbols:**

```
ffffffff81453210-ffffffff81453410: fanotify_info_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fanotify_info_equal(struct fanotify_info *info1, struct fanotify_info *info2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814e20c0)
Location: fs/notify/fanotify/fanotify.c:75
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
**Symbols:**

```
ffffffff814e20c0-ffffffff814e22c4: fanotify_info_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fanotify_info_equal(struct fanotify_info *info1, struct fanotify_info *info2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff815189c0)
Location: fs/notify/fanotify/fanotify.c:75
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
**Symbols:**

```
ffffffff815189c0-ffffffff81518b91: fanotify_info_equal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fanotify_info_equal(struct fanotify_info *info1, struct fanotify_info *info2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8154cda0)
Location: fs/notify/fanotify/fanotify.c:69
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_should_merge
```
**Symbols:**

```
ffffffff8154cda0-ffffffff8154cf71: fanotify_info_equal (STB_LOCAL)
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
