# Function: <code>put_watch_queue</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_watch_queue(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124c733)
Location: kernel/watch_queue.c:385
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
Direct callers:
  - fs/pipe.c:free_pipe_info
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff8124c6e0-ffffffff8124c71b: put_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_watch_queue(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81256b73)
Location: kernel/watch_queue.c:385
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
Direct callers:
  - fs/pipe.c:free_pipe_info
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81256b20-ffffffff81256b5b: put_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_watch_queue(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125b013)
Location: kernel/watch_queue.c:385
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
Direct callers:
  - fs/pipe.c:free_pipe_info
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff8125afc0-ffffffff8125affb: put_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_watch_queue(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81296e13)
Location: kernel/watch_queue.c:388
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
Direct callers:
  - fs/pipe.c:free_pipe_info
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81296dc0-ffffffff81296dfb: put_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_watch_queue(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812ed403)
Location: kernel/watch_queue.c:411
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
Direct callers:
  - fs/pipe.c:free_pipe_info
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff812ed390-ffffffff812ed3ef: put_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_watch_queue(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813577c3)
Location: kernel/watch_queue.c:411
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
Direct callers:
  - fs/pipe.c:free_pipe_info
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81357740-ffffffff8135779f: put_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_watch_queue(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81389033)
Location: kernel/watch_queue.c:408
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
Direct callers:
  - fs/pipe.c:free_pipe_info
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81388fb0-ffffffff8138900f: put_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_watch_queue(struct watch_queue *wqueue);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b2a83)
Location: kernel/watch_queue.c:408
Inline: True
Inline callers:
  - kernel/watch_queue.c:free_watch
Direct callers:
  - fs/pipe.c:free_pipe_info
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff813b2a00-ffffffff813b2a5f: put_watch_queue (STB_GLOBAL)
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
