# Function: <code>__kthread_create_on_node</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8a60)
Location: kernel/kthread.c:265
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810a8a60-ffffffff810a8c0d: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a5840)
Location: kernel/kthread.c:269
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810a5840-ffffffff810a59ed: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810abf50)
Location: kernel/kthread.c:276
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810abf50-ffffffff810ac0fc: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b31c0)
Location: kernel/kthread.c:284
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810b31c0-ffffffff810b3383: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc300)
Location: kernel/kthread.c:284
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810bc300-ffffffff810bc4c3: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1ab0)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810c1ab0-ffffffff810c1c67: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c8000)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810c8000-ffffffff810c81b7: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0c00)
Location: kernel/kthread.c:329
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810d0c00-ffffffff810d0db7: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb6b0)
Location: kernel/kthread.c:330
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810cb6b0-ffffffff810cb86d: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ccf30)
Location: kernel/kthread.c:357
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810ccf30-ffffffff810cd0ed: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0100)
Location: kernel/kthread.c:357
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810e0100-ffffffff810e02bd: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f9d00)
Location: kernel/kthread.c:414
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810f9d00-ffffffff810f9f11: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111ca50)
Location: kernel/kthread.c:414
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff8111ca50-ffffffff8111cc61: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129be0)
Location: kernel/kthread.c:429
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff81129be0-ffffffff81129d85: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134220)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff81134220-ffffffff811343f2: __kthread_create_on_node (STB_LOCAL)
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
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127b70)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffff800010127b70-ffff800010127d84: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037af20)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
c037af20-c037b110: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000171780)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
c000000000171780-c000000000171a08: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, va_list args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df5ca)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffe0000df5ca-ffffffe0000df778: __kthread_create_on_node (STB_LOCAL)
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
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2380)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810c2380-ffffffff810c2537: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b0bd0)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810b0bd0-ffffffff810b0d87: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c18d0)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810c18d0-ffffffff810c1a87: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *__kthread_create_on_node(int (*threadfn)(void *), void *data, int node, const char *namefmt, struct __va_list_tag *args);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c9d00)
Location: kernel/kthread.c:293
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:kthread_create_on_node
```
**Symbols:**

```
ffffffff810c9d00-ffffffff810c9eb5: __kthread_create_on_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
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
