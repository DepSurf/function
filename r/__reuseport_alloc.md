# Function: <code>__reuseport_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817a03cd)
Location: net/core/sock_reuseport.c:16
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ced9d)
Location: net/core/sock_reuseport.c:16
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff817ee145)
Location: net/core/sock_reuseport.c:16
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff8186a395)
Location: net/core/sock_reuseport.c:17
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffff818ba0be)
Location: net/core/sock_reuseport.c:17
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffff818e0ee1)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffff8192f6b5)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffff81961925)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock_reuseport *__reuseport_alloc(unsigned int max_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a34d00)
Location: net/core/sock_reuseport.c:21
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
**Symbols:**

```
ffffffff81a34d00-ffffffff81a34d34: __reuseport_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sock_reuseport *__reuseport_alloc(unsigned int max_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a37040)
Location: net/core/sock_reuseport.c:21
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
**Symbols:**

```
ffffffff81a37040-ffffffff81a37074: __reuseport_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sock_reuseport *__reuseport_alloc(unsigned int max_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81a1e1a0)
Location: net/core/sock_reuseport.c:21
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
**Symbols:**

```
ffffffff81a1e1a0-ffffffff81a1e1d4: __reuseport_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock_reuseport *__reuseport_alloc(unsigned int max_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1af0)
Location: net/core/sock_reuseport.c:90
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/sock_reuseport.c:reuseport_alloc
```
**Symbols:**

```
ffffffff81ad1af0-ffffffff81ad1b24: __reuseport_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock_reuseport *__reuseport_alloc(unsigned int max_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4f350)
Location: net/core/sock_reuseport.c:90
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/sock_reuseport.c:reuseport_alloc
```
**Symbols:**

```
ffffffff81c4f350-ffffffff81c4f38c: __reuseport_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock_reuseport *__reuseport_alloc(unsigned int max_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e047c0)
Location: net/core/sock_reuseport.c:174
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/sock_reuseport.c:reuseport_alloc
```
**Symbols:**

```
ffffffff81e047c0-ffffffff81e047fc: __reuseport_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock_reuseport *__reuseport_alloc(unsigned int max_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e77010)
Location: net/core/sock_reuseport.c:174
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/sock_reuseport.c:reuseport_alloc
```
**Symbols:**

```
ffffffff81e77010-ffffffff81e7704c: __reuseport_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock_reuseport *__reuseport_alloc(unsigned int max_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f36fd0)
Location: net/core/sock_reuseport.c:174
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
  - net/core/sock_reuseport.c:reuseport_alloc
```
**Symbols:**

```
ffffffff81f36fd0-ffffffff81f3700c: __reuseport_alloc (STB_LOCAL)
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
In net/core/sock_reuseport.c (ffff800010c054c8)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (c0d1e6d0)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (c000000000cef660)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffe000783dba)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffff819018f5)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffff818bb725)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffff81952925)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
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
In net/core/sock_reuseport.c (ffffffff81974395)
Location: net/core/sock_reuseport.c:40
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
  - net/core/sock_reuseport.c:reuseport_alloc
```
</details>
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
