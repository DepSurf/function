# Function: <code>sock_bindtoindex_locked</code>

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
int sock_bindtoindex_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e3680)
Location: net/core/sock.c:569
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819e3680-ffffffff819e3706: sock_bindtoindex_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sock_bindtoindex_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819e31d0)
Location: net/core/sock.c:559
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819e31d0-ffffffff819e3256: sock_bindtoindex_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sock_bindtoindex_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819c9220)
Location: net/core/sock.c:567
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819c9220-ffffffff819c92a6: sock_bindtoindex_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sock_bindtoindex_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a785c0)
Location: net/core/sock.c:586
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81a785c0-ffffffff81a78646: sock_bindtoindex_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sock_bindtoindex_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bebee0)
Location: net/core/sock.c:623
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81bebee0-ffffffff81bebf70: sock_bindtoindex_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sock_bindtoindex_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d988a0)
Location: net/core/sock.c:623
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_bindtoindex
  - net/core/sock.c:sock_bindtoindex
```
**Symbols:**

```
ffffffff81d988a0-ffffffff81d98930: sock_bindtoindex_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sock_bindtoindex_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e06f30)
Location: net/core/sock.c:629
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_bindtoindex
  - net/core/sock.c:sock_bindtoindex
```
**Symbols:**

```
ffffffff81e06f30-ffffffff81e06fc0: sock_bindtoindex_locked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sock_bindtoindex_locked(struct sock *sk, int ifindex);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec3790)
Location: net/core/sock.c:626
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sock_bindtoindex
  - net/core/sock.c:sock_bindtoindex
```
**Symbols:**

```
ffffffff81ec3790-ffffffff81ec3820: sock_bindtoindex_locked (STB_LOCAL)
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
