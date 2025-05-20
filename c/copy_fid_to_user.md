# Function: <code>copy_fid_to_user</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff8131e010)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff8131e010-ffffffff8131e1ce: copy_fid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81330e50)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81330e50-ffffffff8133100e: copy_fid_to_user (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffff8000103ee218)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffff8000103ee218-ffff8000103ee4b4: copy_fid_to_user (STB_LOCAL)
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
In fs/notify/fanotify/fanotify_user.c (c05c5204)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (c0000000004f5f60)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
c0000000004f5f60-c0000000004f61d8: copy_fid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffe0002a1706)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffe0002a1706-ffffffe0002a1846: copy_fid_to_user (STB_LOCAL)
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
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81329430)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81329430-ffffffff813295ee: copy_fid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81319fd0)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81319fd0-ffffffff8131a18e: copy_fid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81326f00)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81326f00-ffffffff813270be: copy_fid_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int copy_fid_to_user(struct fanotify_event *event, char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify_user.c (ffffffff81338df0)
Location: fs/notify/fanotify/fanotify_user.c:207
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_read
```
**Symbols:**

```
ffffffff81338df0-ffffffff81338fae: copy_fid_to_user (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
