# Function: <code>find_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd9b0)
Location: drivers/xen/xenbus/xenbus_xs.c:646
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:process_msg
```
**Symbols:**

```
ffffffff814cd9b0-ffffffff814cd9ee: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151e520)
Location: drivers/xen/xenbus/xenbus_xs.c:641
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
```
**Symbols:**

```
ffffffff8151e520-ffffffff8151e55e: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a9a0)
Location: drivers/xen/xenbus/xenbus_xs.c:656
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_thread
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
```
**Symbols:**

```
ffffffff8154a9a0-ffffffff8154a9de: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155e530)
Location: drivers/xen/xenbus/xenbus_xs.c:673
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff8155e530-ffffffff8155e56e: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c2850)
Location: drivers/xen/xenbus/xenbus_xs.c:676
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff815c2850-ffffffff815c288e: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fae90)
Location: drivers/xen/xenbus/xenbus_xs.c:678
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff815fae90-ffffffff815faed4: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81615f40)
Location: drivers/xen/xenbus/xenbus_xs.c:678
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff81615f40-ffffffff81615f84: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81649ba0)
Location: drivers/xen/xenbus/xenbus_xs.c:681
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff81649ba0-ffffffff81649bdf: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166c040)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff8166c040-ffffffff8166c07f: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d721)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8173a6e1)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171dee7)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179cc97)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d62d5)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a287b5)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a71eb5)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
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
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac4015)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
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
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff800010836440)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffff800010836440-ffff8000108364b4: find_watch (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81631eb0)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff81631eb0-ffffffff81631eef: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8165fe80)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff8165fe80-ffffffff8165febf: find_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xenbus_watch *find_watch(const char *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167a4d0)
Location: drivers/xen/xenbus/xenbus_xs.c:684
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:register_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch_msg
```
**Symbols:**

```
ffffffff8167a4d0-ffffffff8167a50f: find_watch (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
