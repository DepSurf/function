# Function: <code>fsnotify_remove_queued_event</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81319e80)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81319e80-ffffffff81319e8b: fsnotify_remove_queued_event.part.0 (STB_LOCAL)
ffffffff8131a090-ffffffff8131a0bf: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff8132ccb0)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff8132ccb0-ffffffff8132ccbb: fsnotify_remove_queued_event.part.0 (STB_LOCAL)
ffffffff8132cec0-ffffffff8132ceef: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81366c80)
Location: fs/notify/notification.c:131
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
**Symbols:**

```
ffffffff81366c30-ffffffff81366c5d: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81373fd0)
Location: fs/notify/notification.c:131
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
**Symbols:**

```
ffffffff81373f80-ffffffff81373fad: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8137a978)
Location: fs/notify/notification.c:132
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
```
**Symbols:**

```
ffffffff8137a8d0-ffffffff8137a8fd: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff813c75f5)
Location: fs/notify/notification.c:132
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
**Symbols:**

```
ffffffff813c7550-ffffffff813c757d: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff8144ea19)
Location: fs/notify/notification.c:132
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
**Symbols:**

```
ffffffff8144e950-ffffffff8144e989: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff814dd189)
Location: fs/notify/notification.c:132
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
**Symbols:**

```
ffffffff814dd0a0-ffffffff814dd0d9: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff815139e9)
Location: fs/notify/notification.c:132
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
**Symbols:**

```
ffffffff81513900-ffffffff81513939: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffff81547e79)
Location: fs/notify/notification.c:132
Inline: True
Inline callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
```
**Symbols:**

```
ffffffff81547d90-ffffffff81547dc9: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffff8000103e87c8)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffff8000103e87c8-ffff8000103e87dc: fsnotify_remove_queued_event.part.0 (STB_LOCAL)
ffff8000103e8b08-ffff8000103e8b5c: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (c05c0128)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
c05c0128-c05c0140: fsnotify_remove_queued_event.part.0 (STB_LOCAL)
c05c033c-c05c0388: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (c0000000004ef600)
Location: fs/notify/notification.c:131
Inline: False
Direct callers:
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/notification.c:fsnotify_remove_first_event
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
c0000000004ef600-c0000000004ef644: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/notification.c (ffffffe00029d6e6)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffe00029d6e6-ffffffe00029d72c: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81325290)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81325290-ffffffff8132529b: fsnotify_remove_queued_event.part.0 (STB_LOCAL)
ffffffff813254a0-ffffffff813254cf: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81315e30)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81315e30-ffffffff81315e3b: fsnotify_remove_queued_event.part.0 (STB_LOCAL)
ffffffff81316040-ffffffff8131606f: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81322d60)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81322d60-ffffffff81322d6b: fsnotify_remove_queued_event.part.0 (STB_LOCAL)
ffffffff81322f70-ffffffff81322f9f: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fsnotify_remove_queued_event(struct fsnotify_group *group, struct fsnotify_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/notification.c (ffffffff81334b00)
Location: fs/notify/notification.c:131
Inline: True
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_handle_event
```
**Symbols:**

```
ffffffff81334b00-ffffffff81334b0b: fsnotify_remove_queued_event.part.0 (STB_LOCAL)
ffffffff81334cb0-ffffffff81334cdf: fsnotify_remove_queued_event (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
