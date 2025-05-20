# Function: <code>get_watch_queue</code>

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
struct watch_queue *get_watch_queue(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8124c630)
Location: kernel/watch_queue.c:625
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff8124c630-ffffffff8124c6d4: get_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct watch_queue *get_watch_queue(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81256a70)
Location: kernel/watch_queue.c:625
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81256a70-ffffffff81256b14: get_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct watch_queue *get_watch_queue(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff8125af10)
Location: kernel/watch_queue.c:625
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff8125af10-ffffffff8125afb4: get_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct watch_queue *get_watch_queue(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81296d10)
Location: kernel/watch_queue.c:628
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81296d10-ffffffff81296db4: get_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct watch_queue *get_watch_queue(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff812ece10)
Location: kernel/watch_queue.c:662
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff812ece10-ffffffff812eced0: get_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct watch_queue *get_watch_queue(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81357180)
Location: kernel/watch_queue.c:662
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81357180-ffffffff81357240: get_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct watch_queue *get_watch_queue(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff81388a00)
Location: kernel/watch_queue.c:662
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff81388a00-ffffffff81388ac0: get_watch_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct watch_queue *get_watch_queue(int fd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/watch_queue.c (ffffffff813b2460)
Location: kernel/watch_queue.c:662
Inline: False
Direct callers:
  - security/keys/keyctl.c:keyctl_watch_key
```
**Symbols:**

```
ffffffff813b2460-ffffffff813b2520: get_watch_queue (STB_GLOBAL)
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
