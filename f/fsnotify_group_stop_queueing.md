# Function: <code>fsnotify_group_stop_queueing</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8127851b)
Location: fs/notify/group.c:47
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff812784e0-ffffffff8127850e: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8128c1d0)
Location: fs/notify/group.c:47
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8128c1d0-ffffffff8128c200: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81299160)
Location: fs/notify/group.c:47
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81299160-ffffffff81299190: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff812bc520)
Location: fs/notify/group.c:47
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff812bc520-ffffffff812bc550: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff812e5199)
Location: fs/notify/group.c:47
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff812e5140-ffffffff812e5170: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff812f9ce9)
Location: fs/notify/group.c:50
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff812f9c90-ffffffff812f9cc0: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8131a3aa)
Location: fs/notify/group.c:36
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8131a350-ffffffff8131a37e: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8132d1ca)
Location: fs/notify/group.c:36
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8132d170-ffffffff8132d19e: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81366f30)
Location: fs/notify/group.c:37
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81366f30-ffffffff81366f5e: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81374280)
Location: fs/notify/group.c:37
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81374280-ffffffff813742ae: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8137abe0)
Location: fs/notify/group.c:37
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8137abe0-ffffffff8137ac0e: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff813c78c0)
Location: fs/notify/group.c:37
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff813c78c0-ffffffff813c78ee: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8144ed39)
Location: fs/notify/group.c:37
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff8144ecd0-ffffffff8144ed02: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff814dd4f9)
Location: fs/notify/group.c:37
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff814dd480-ffffffff814dd4b2: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81513d59)
Location: fs/notify/group.c:37
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81513ce0-ffffffff81513d12: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81548229)
Location: fs/notify/group.c:37
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff815481b0-ffffffff815481e2: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffff8000103e9060)
Location: fs/notify/group.c:36
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffff8000103e8f98-ffff8000103e9038: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (c05c06b0)
Location: fs/notify/group.c:36
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
c05c06b0-c05c06f4: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (c0000000004efb20)
Location: fs/notify/group.c:36
Inline: False
Direct callers:
  - fs/notify/group.c:fsnotify_destroy_group
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
c0000000004efb20-c0000000004efbd8: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffe00029dafc)
Location: fs/notify/group.c:36
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffe00029da72-ffffffe00029dae4: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff813257aa)
Location: fs/notify/group.c:36
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81325750-ffffffff8132577e: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8131634a)
Location: fs/notify/group.c:36
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff813162f0-ffffffff8131631e: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff8132327a)
Location: fs/notify/group.c:36
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81323220-ffffffff8132324e: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fsnotify_group_stop_queueing(struct fsnotify_group *group);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/group.c (ffffffff81334fca)
Location: fs/notify/group.c:36
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_destroy_group
Direct callers:
  - fs/notify/fanotify/fanotify_user.c:fanotify_release
```
**Symbols:**

```
ffffffff81334f70-ffffffff81334f9c: fsnotify_group_stop_queueing (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
