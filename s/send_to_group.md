# Function: <code>send_to_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8124f3a3)
Location: fs/notify/fsnotify.c:125
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81277b05)
Location: fs/notify/fsnotify.c:125
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8128b7e5)
Location: fs/notify/fsnotify.c:125
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812986b1)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812bb971)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff812e468b)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff812f91d7)
Location: fs/notify/fsnotify.c:195
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff8131982c)
Location: fs/notify/fsnotify.c:182
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff8132c65c)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int send_to_group(struct inode *to_tell, __u32 mask, const void *data, int data_is, u32 cookie, const struct qstr *file_name, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813661c0)
Location: fs/notify/fsnotify.c:179
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff813661c0-ffffffff8136630f: send_to_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int send_to_group(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81373210)
Location: fs/notify/fsnotify.c:314
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff81373210-ffffffff81373454: send_to_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int send_to_group(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81379af0)
Location: fs/notify/fsnotify.c:314
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff81379af0-ffffffff81379d34: send_to_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int send_to_group(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813c6650)
Location: fs/notify/fsnotify.c:314
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff813c6650-ffffffff813c6923: send_to_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int send_to_group(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff8144d690)
Location: fs/notify/fsnotify.c:320
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff8144d690-ffffffff8144d9dc: send_to_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int send_to_group(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff814dbca0)
Location: fs/notify/fsnotify.c:320
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff814dbca0-ffffffff814dc08d: send_to_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int send_to_group(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fsnotify.c (0)
Location: fs/notify/fsnotify.c:320
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff81512490-ffffffff81512877: send_to_group (STB_LOCAL)
ffffffff820e9cce-ffffffff820e9d4f: send_to_group.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int send_to_group(__u32 mask, const void *data, int data_type, struct inode *dir, const struct qstr *file_name, u32 cookie, struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fsnotify.c (0)
Location: fs/notify/fsnotify.c:320
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff81546940-ffffffff81546d27: send_to_group (STB_LOCAL)
ffffffff821c6783-ffffffff821c6804: send_to_group.cold (STB_LOCAL)
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
In fs/notify/fsnotify.c (ffff8000103e7f74)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (c05bfa9c)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (c0000000004ee9a0)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffe00029cc58)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff81324c3c)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff813157dc)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff8132270c)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff8133456c)
Location: fs/notify/fsnotify.c:186
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int data_type</code>
</li>
<li>
<b>Param added. </b>
<code>struct inode *dir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *to_tell</code>
</li>
<li>
<b>Param removed. </b>
<code>int data_is</code>
</li>
<li>
<b>Param reordered. </b>
<code>to_tell, mask, data, data_is, cookie, file_name, iter_info</code> ➡️ <code>mask, data, data_type, dir, file_name, cookie, iter_info</code>
</li>
</ul>
</details>
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
