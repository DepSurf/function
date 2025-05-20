# Function: <code>fanotify_should_merge</code>

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
bool fanotify_should_merge(struct fsnotify_event *old_fsn, struct fsnotify_event *new_fsn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8136a590)
Location: fs/notify/fanotify/fanotify.c:73
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
**Symbols:**

```
ffffffff8136a590-ffffffff8136a6e8: fanotify_should_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool fanotify_should_merge(struct fsnotify_event *old_fsn, struct fsnotify_event *new_fsn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813777c0)
Location: fs/notify/fanotify/fanotify.c:91
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
**Symbols:**

```
ffffffff813777c0-ffffffff813778da: fanotify_should_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool fanotify_should_merge(struct fanotify_event *old, struct fanotify_event *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8137e070)
Location: fs/notify/fanotify/fanotify.c:114
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
**Symbols:**

```
ffffffff8137e070-ffffffff8137e29a: fanotify_should_merge (STB_LOCAL)
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
In fs/notify/fanotify/fanotify.c (ffffffff813cb00c)
Location: fs/notify/fanotify/fanotify.c:114
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
bool fanotify_should_merge(struct fanotify_event *old, struct fanotify_event *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81453410)
Location: fs/notify/fanotify/fanotify.c:136
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
**Symbols:**

```
ffffffff81453410-ffffffff81453577: fanotify_should_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool fanotify_should_merge(struct fanotify_event *old, struct fanotify_event *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814e22e0)
Location: fs/notify/fanotify/fanotify.c:136
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
**Symbols:**

```
ffffffff814e22e0-ffffffff814e2447: fanotify_should_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool fanotify_should_merge(struct fanotify_event *old, struct fanotify_event *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81518bb0)
Location: fs/notify/fanotify/fanotify.c:136
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
**Symbols:**

```
ffffffff81518bb0-ffffffff81518d1b: fanotify_should_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool fanotify_should_merge(struct fanotify_event *old, struct fanotify_event *new);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8154cf90)
Location: fs/notify/fanotify/fanotify.c:130
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_merge
```
**Symbols:**

```
ffffffff8154cf90-ffffffff8154d0fb: fanotify_should_merge (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fanotify_event *old</code>
</li>
<li>
<b>Param added. </b>
<code>struct fanotify_event *new</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_event *old_fsn</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fsnotify_event *new_fsn</code>
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
