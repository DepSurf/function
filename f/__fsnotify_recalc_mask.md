# Function: <code>__fsnotify_recalc_mask</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81299540)
Location: fs/notify/mark.c:123
Inline: True
```
**Symbols:**

```
ffffffff81299540-ffffffff81299596: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812bc8b0)
Location: fs/notify/mark.c:113
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff812bc8b0-ffffffff812bc905: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812e5320)
Location: fs/notify/mark.c:112
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff812e5320-ffffffff812e5376: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff812f9f90)
Location: fs/notify/mark.c:131
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff812f9f90-ffffffff812f9fed: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8131a630)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff8131a630-ffffffff8131a692: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8132d470)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff8132d470-ffffffff8132d4d2: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81367110)
Location: fs/notify/mark.c:119
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81367110-ffffffff81367172: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81374460)
Location: fs/notify/mark.c:119
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81374460-ffffffff813744d8: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8137ae10)
Location: fs/notify/mark.c:119
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff8137ae10-ffffffff8137ae88: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813c7a00)
Location: fs/notify/mark.c:119
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff813c7a00-ffffffff813c7a78: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff8144eed0)
Location: fs/notify/mark.c:156
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff8144eed0-ffffffff8144f006: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff814dd6c0)
Location: fs/notify/mark.c:156
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff814dd6c0-ffffffff814dd7f4: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81513f20)
Location: fs/notify/mark.c:156
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81513f20-ffffffff81514054: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff815483f0)
Location: fs/notify/mark.c:156
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_add_mark_locked
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff815483f0-ffffffff81548524: __fsnotify_recalc_mask (STB_LOCAL)
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
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffff8000103e92f8)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffff8000103e92f8-ffff8000103e9388: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c05c0b88)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
c05c0b88-c05c0c24: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (c0000000004efd80)
Location: fs/notify/mark.c:119
Inline: False
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
c0000000004efd80-c0000000004efe28: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffe00029ddf8)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffe00029ddf8-ffffffe00029de62: __fsnotify_recalc_mask (STB_LOCAL)
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
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81325a50)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81325a50-ffffffff81325ab2: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813165f0)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff813165f0-ffffffff81316652: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff81323520)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff81323520-ffffffff81323582: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __fsnotify_recalc_mask(struct fsnotify_mark_connector *conn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/notify/mark.c (ffffffff813353b0)
Location: fs/notify/mark.c:119
Inline: True
Direct callers:
  - fs/notify/mark.c:fsnotify_put_mark
```
**Symbols:**

```
ffffffff813353b0-ffffffff81335412: __fsnotify_recalc_mask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>void *</code>
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
