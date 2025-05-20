# Function: <code>fsnotify_put_sb_connectors</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsnotify_put_sb_connectors(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c7a80)
Location: fs/notify/mark.c:195
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_list
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
**Symbols:**

```
ffffffff813c7a80-ffffffff813c7ae0: fsnotify_put_sb_connectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fsnotify_put_sb_connectors(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144f080)
Location: fs/notify/mark.c:233
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
**Symbols:**

```
ffffffff8144f080-ffffffff8144f0f0: fsnotify_put_sb_connectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fsnotify_put_sb_connectors(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814dd890)
Location: fs/notify/mark.c:233
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
**Symbols:**

```
ffffffff814dd890-ffffffff814dd900: fsnotify_put_sb_connectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fsnotify_put_sb_connectors(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815140f0)
Location: fs/notify/mark.c:233
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
**Symbols:**

```
ffffffff815140f0-ffffffff81514160: fsnotify_put_sb_connectors (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fsnotify_put_sb_connectors(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815485c0)
Location: fs/notify/mark.c:233
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_detach_connector_from_object
```
**Symbols:**

```
ffffffff815485c0-ffffffff81548630: fsnotify_put_sb_connectors (STB_LOCAL)
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
