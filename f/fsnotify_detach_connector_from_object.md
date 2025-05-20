# Function: <code>fsnotify_detach_connector_from_object</code>

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
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (ffffffff812995a0)
Location: fs/notify/mark.c:175
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
```
**Symbols:**

```
ffffffff812995a0-ffffffff81299602: fsnotify_detach_connector_from_object.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/notify/mark.c (ffffffff812bc910)
Location: fs/notify/mark.c:165
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff812bc910-ffffffff812bc972: fsnotify_detach_connector_from_object.isra.5 (STB_LOCAL)
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
In fs/notify/mark.c (ffffffff812e6070)
Location: fs/notify/mark.c:164
Inline: True
Inline callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812f9dd0)
Location: fs/notify/mark.c:184
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff812f9dd0-ffffffff812f9e4f: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131a4a0)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff8131a4a0-ffffffff8131a531: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d2c0)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff8132d2c0-ffffffff8132d351: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367070)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81367070-ffffffff81367101: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813743c0)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff813743c0-ffffffff81374451: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137ad70)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff8137ad70-ffffffff8137ae01: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c7ae0)
Location: fs/notify/mark.c:203
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff813c7ae0-ffffffff813c7b73: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144f0f0)
Location: fs/notify/mark.c:241
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff8144f0f0-ffffffff8144f190: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814dd910)
Location: fs/notify/mark.c:241
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff814dd910-ffffffff814dd9b0: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81514170)
Location: fs/notify/mark.c:241
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81514170-ffffffff81514210: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81548640)
Location: fs/notify/mark.c:241
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81548640-ffffffff815486e0: fsnotify_detach_connector_from_object (STB_LOCAL)
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
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e9408)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffff8000103e9408-ffff8000103e94cc: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c0808)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
c05c0808-c05c08b0: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004efe30)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
c0000000004efe30-c0000000004eff18: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029dc44)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffe00029dc44-ffffffe00029dcce: fsnotify_detach_connector_from_object (STB_LOCAL)
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
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813258a0)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff813258a0-ffffffff81325931: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81316440)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81316440-ffffffff813164d1: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323370)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81323370-ffffffff81323401: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *fsnotify_detach_connector_from_object(struct fsnotify_mark_connector *conn, unsigned int *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813350c0)
Location: fs/notify/mark.c:172
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_destroy_marks
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff813350c0-ffffffff81335151: fsnotify_detach_connector_from_object (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
