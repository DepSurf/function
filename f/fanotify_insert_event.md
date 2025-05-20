# Function: <code>fanotify_insert_event</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fanotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *fsn_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8137ddd0)
Location: fs/notify/fanotify/fanotify.c:696
Inline: False
```
**Symbols:**

```
ffffffff8137ddd0-ffffffff8137de4b: fanotify_insert_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fanotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *fsn_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff813cad10)
Location: fs/notify/fanotify/fanotify.c:696
Inline: False
```
**Symbols:**

```
ffffffff813cad10-ffffffff813cad88: fanotify_insert_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fanotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *fsn_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81452aa0)
Location: fs/notify/fanotify/fanotify.c:867
Inline: False
```
**Symbols:**

```
ffffffff81452aa0-ffffffff81452b57: fanotify_insert_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fanotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *fsn_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814e1760)
Location: fs/notify/fanotify/fanotify.c:870
Inline: False
```
**Symbols:**

```
ffffffff814e1760-ffffffff814e1817: fanotify_insert_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fanotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *fsn_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81518020)
Location: fs/notify/fanotify/fanotify.c:874
Inline: False
```
**Symbols:**

```
ffffffff81518020-ffffffff815180d7: fanotify_insert_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fanotify_insert_event(struct fsnotify_group *group, struct fsnotify_event *fsn_event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8154c400)
Location: fs/notify/fanotify/fanotify.c:860
Inline: False
```
**Symbols:**

```
ffffffff8154c400-ffffffff8154c4b7: fanotify_insert_event (STB_LOCAL)
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
