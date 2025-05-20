# Function: <code>fsnotify_iter_select_report_types</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff812e45f2)
Location: fs/notify/fsnotify.c:267
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
In fs/notify/fsnotify.c (ffffffff812f9143)
Location: fs/notify/fsnotify.c:276
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
In fs/notify/fsnotify.c (ffffffff8131979f)
Location: fs/notify/fsnotify.c:263
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
In fs/notify/fsnotify.c (ffffffff8132c5cf)
Location: fs/notify/fsnotify.c:267
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
unsigned int fsnotify_iter_select_report_types(struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff81366310)
Location: fs/notify/fsnotify.c:260
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff81366310-ffffffff813663b6: fsnotify_iter_select_report_types (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int fsnotify_iter_select_report_types(struct fsnotify_iter_info *iter_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fsnotify.c (ffffffff813730d0)
Location: fs/notify/fsnotify.c:397
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify
  - fs/notify/fsnotify.c:fsnotify
```
**Symbols:**

```
ffffffff813730d0-ffffffff81373176: fsnotify_iter_select_report_types (STB_LOCAL)
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
In fs/notify/fsnotify.c (ffffffff81379eef)
Location: fs/notify/fsnotify.c:397
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff813c6aef)
Location: fs/notify/fsnotify.c:397
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff8144db9f)
Location: fs/notify/fsnotify.c:395
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff814dc25f)
Location: fs/notify/fsnotify.c:397
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff81512a4f)
Location: fs/notify/fsnotify.c:397
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffffffff81546eff)
Location: fs/notify/fsnotify.c:397
Inline: True
Inline callers:
  - fs/notify/fsnotify.c:fsnotify
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
In fs/notify/fsnotify.c (ffff8000103e7e90)
Location: fs/notify/fsnotify.c:267
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
In fs/notify/fsnotify.c (c05bfa00)
Location: fs/notify/fsnotify.c:267
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
In fs/notify/fsnotify.c (c0000000004ee8f0)
Location: fs/notify/fsnotify.c:267
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
In fs/notify/fsnotify.c (ffffffe00029cc56)
Location: fs/notify/fsnotify.c:267
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
In fs/notify/fsnotify.c (ffffffff81324baf)
Location: fs/notify/fsnotify.c:267
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
In fs/notify/fsnotify.c (ffffffff8131574f)
Location: fs/notify/fsnotify.c:267
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
In fs/notify/fsnotify.c (ffffffff8132267f)
Location: fs/notify/fsnotify.c:267
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
In fs/notify/fsnotify.c (ffffffff813344df)
Location: fs/notify/fsnotify.c:267
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
