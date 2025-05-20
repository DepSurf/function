# Function: <code>remove_watch_from_object</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int remove_watch_from_object(struct watch_list *wlist, struct watch_queue *wq, u64 id, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124ccc0)
Location: kernel/watch_queue.c:484
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff8124ccc0-ffffffff8124cf28: remove_watch_from_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int remove_watch_from_object(struct watch_list *wlist, struct watch_queue *wq, u64 id, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81257110)
Location: kernel/watch_queue.c:484
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81257110-ffffffff81257386: remove_watch_from_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int remove_watch_from_object(struct watch_list *wlist, struct watch_queue *wq, u64 id, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125b470)
Location: kernel/watch_queue.c:484
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff8125b470-ffffffff8125b6e3: remove_watch_from_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int remove_watch_from_object(struct watch_list *wlist, struct watch_queue *wq, u64 id, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81297280)
Location: kernel/watch_queue.c:487
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81297280-ffffffff812974f3: remove_watch_from_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int remove_watch_from_object(struct watch_list *wlist, struct watch_queue *wq, u64 id, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:526
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81e6b2b8-ffffffff81e6b2e3: remove_watch_from_object.cold (STB_LOCAL)
ffffffff812ed6a0-ffffffff812ed91c: remove_watch_from_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int remove_watch_from_object(struct watch_list *wlist, struct watch_queue *wq, u64 id, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:526
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff82062029-ffffffff82062054: remove_watch_from_object.cold (STB_LOCAL)
ffffffff81357a80-ffffffff81357cfc: remove_watch_from_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int remove_watch_from_object(struct watch_list *wlist, struct watch_queue *wq, u64 id, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813892e0)
Location: kernel/watch_queue.c:523
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff813892e0-ffffffff81389583: remove_watch_from_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int remove_watch_from_object(struct watch_list *wlist, struct watch_queue *wq, u64 id, bool all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b2d30)
Location: kernel/watch_queue.c:523
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff813b2d30-ffffffff813b2fd3: remove_watch_from_object (STB_GLOBAL)
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
