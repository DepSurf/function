# Function: <code>SyS_epoll_create1</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_epoll_create1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812559a0)
Location: fs/eventpoll.c:1764
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff812559a0-ffffffff81255a79: SyS_epoll_create1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_epoll_create1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8127e2e5)
Location: fs/eventpoll.c:1793
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff8127e1e0-ffffffff8127e2b9: SyS_epoll_create1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_epoll_create1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff81291e75)
Location: fs/eventpoll.c:1793
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff81291d70-ffffffff81291e49: SyS_epoll_create1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_epoll_create1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff8129ef25)
Location: fs/eventpoll.c:1954
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff8129ee20-ffffffff8129eef5: SyS_epoll_create1 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_epoll_create1(long int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/eventpoll.c (ffffffff812c2395)
Location: fs/eventpoll.c:1936
Inline: True
Inline callers:
  - fs/eventpoll.c:SyS_epoll_create
```
**Symbols:**

```
ffffffff812c2290-ffffffff812c2365: SyS_epoll_create1 (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
