# Function: <code>add_watch_to_object</code>

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
int add_watch_to_object(struct watch *watch, struct watch_list *wlist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124c790)
Location: kernel/watch_queue.c:442
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff8124c790-ffffffff8124c963: add_watch_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_watch_to_object(struct watch *watch, struct watch_list *wlist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81256bd0)
Location: kernel/watch_queue.c:442
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81256bd0-ffffffff81256da3: add_watch_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int add_watch_to_object(struct watch *watch, struct watch_list *wlist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125b070)
Location: kernel/watch_queue.c:442
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff8125b070-ffffffff8125b23f: add_watch_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int add_watch_to_object(struct watch *watch, struct watch_list *wlist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81296e70)
Location: kernel/watch_queue.c:445
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81296e70-ffffffff8129703f: add_watch_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int add_watch_to_object(struct watch *watch, struct watch_list *wlist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:496
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81e6b2a3-ffffffff81e6b2b8: add_watch_to_object.cold (STB_LOCAL)
ffffffff812ed490-ffffffff812ed697: add_watch_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int add_watch_to_object(struct watch *watch, struct watch_list *wlist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/watch_queue.c (0)
Location: kernel/watch_queue.c:496
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff82062014-ffffffff82062029: add_watch_to_object.cold (STB_LOCAL)
ffffffff81357860-ffffffff81357a67: add_watch_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_watch_to_object(struct watch *watch, struct watch_list *wlist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813890d0)
Location: kernel/watch_queue.c:493
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff813890d0-ffffffff813892c9: add_watch_to_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_watch_to_object(struct watch *watch, struct watch_list *wlist);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b2b20)
Location: kernel/watch_queue.c:493
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff813b2b20-ffffffff813b2d1b: add_watch_to_object (STB_GLOBAL)
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
