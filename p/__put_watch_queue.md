# Function: <code>__put_watch_queue</code>

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
void __put_watch_queue(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124c5c0)
Location: kernel/watch_queue.c:365
Inline: False
Direct callers:
  - kernel/watch_queue.c:free_watch
```
**Symbols:**

```
ffffffff8124c5c0-ffffffff8124c622: __put_watch_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __put_watch_queue(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81256a00)
Location: kernel/watch_queue.c:365
Inline: False
Direct callers:
  - kernel/watch_queue.c:free_watch
```
**Symbols:**

```
ffffffff81256a00-ffffffff81256a62: __put_watch_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __put_watch_queue(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125aea0)
Location: kernel/watch_queue.c:365
Inline: False
Direct callers:
  - kernel/watch_queue.c:free_watch
```
**Symbols:**

```
ffffffff8125aea0-ffffffff8125af02: __put_watch_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __put_watch_queue(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81296ca0)
Location: kernel/watch_queue.c:367
Inline: False
Direct callers:
  - kernel/watch_queue.c:free_watch
```
**Symbols:**

```
ffffffff81296ca0-ffffffff81296d0c: __put_watch_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __put_watch_queue(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812ecd80)
Location: kernel/watch_queue.c:389
Inline: False
Direct callers:
  - kernel/watch_queue.c:free_watch
```
**Symbols:**

```
ffffffff812ecd80-ffffffff812ece02: __put_watch_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __put_watch_queue(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813570e0)
Location: kernel/watch_queue.c:389
Inline: False
Direct callers:
  - kernel/watch_queue.c:free_watch
```
**Symbols:**

```
ffffffff813570e0-ffffffff81357162: __put_watch_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __put_watch_queue(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81388960)
Location: kernel/watch_queue.c:386
Inline: False
Direct callers:
  - kernel/watch_queue.c:free_watch
```
**Symbols:**

```
ffffffff81388960-ffffffff813889e4: __put_watch_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __put_watch_queue(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b23c0)
Location: kernel/watch_queue.c:386
Inline: False
Direct callers:
  - kernel/watch_queue.c:free_watch
```
**Symbols:**

```
ffffffff813b23c0-ffffffff813b2444: __put_watch_queue (STB_LOCAL)
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
