# Function: <code>inotify_new_group</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fsnotify_group *inotify_new_group(unsigned int max_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81251f60)
Location: fs/notify/inotify/inotify_user.c:632
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff81251f60-ffffffff81252060: inotify_new_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fsnotify_group *inotify_new_group(unsigned int max_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8127a710)
Location: fs/notify/inotify/inotify_user.c:632
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff8127a710-ffffffff8127a813: inotify_new_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fsnotify_group *inotify_new_group(unsigned int max_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8128e2c0)
Location: fs/notify/inotify/inotify_user.c:632
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff8128e2c0-ffffffff8128e3c3: inotify_new_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fsnotify_group *inotify_new_group(unsigned int max_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff8129b1d0)
Location: fs/notify/inotify/inotify_user.c:600
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff8129b1d0-ffffffff8129b2d8: inotify_new_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fsnotify_group *inotify_new_group(unsigned int max_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff812be5e0)
Location: fs/notify/inotify/inotify_user.c:600
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:sys_inotify_init
```
**Symbols:**

```
ffffffff812be5e0-ffffffff812be6e8: inotify_new_group (STB_LOCAL)
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
In fs/notify/inotify/inotify_user.c (ffffffff812e6de1)
Location: fs/notify/inotify/inotify_user.c:618
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff812fb9c1)
Location: fs/notify/inotify/inotify_user.c:625
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff8131c31e)
Location: fs/notify/inotify/inotify_user.c:614
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff8132f0ee)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fsnotify_group *inotify_new_group(unsigned int max_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81369240)
Location: fs/notify/inotify/inotify_user.c:623
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
```
**Symbols:**

```
ffffffff81369240-ffffffff8136935f: inotify_new_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fsnotify_group *inotify_new_group(unsigned int max_events);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/inotify/inotify_user.c (ffffffff81376520)
Location: fs/notify/inotify/inotify_user.c:630
Inline: False
Direct callers:
  - fs/notify/inotify/inotify_user.c:__do_sys_inotify_init
```
**Symbols:**

```
ffffffff81376520-ffffffff8137663f: inotify_new_group (STB_LOCAL)
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
In fs/notify/inotify/inotify_user.c (ffffffff8137ce4e)
Location: fs/notify/inotify/inotify_user.c:629
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff813c9cfe)
Location: fs/notify/inotify/inotify_user.c:634
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff814517d4)
Location: fs/notify/inotify/inotify_user.c:654
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff814e04d4)
Location: fs/notify/inotify/inotify_user.c:654
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff81516d84)
Location: fs/notify/inotify/inotify_user.c:654
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff8154b174)
Location: fs/notify/inotify/inotify_user.c:653
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffff8000103ebd04)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (c05c2dbc)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (c0000000004f36dc)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffe00029ff3c)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff813276ce)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff8131826e)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff8132519e)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
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
In fs/notify/inotify/inotify_user.c (ffffffff8133753e)
Location: fs/notify/inotify/inotify_user.c:623
Inline: True
Inline callers:
  - fs/notify/inotify/inotify_user.c:do_inotify_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
