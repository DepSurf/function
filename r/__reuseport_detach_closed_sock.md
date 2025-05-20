# Function: <code>__reuseport_detach_closed_sock</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1daa)
Location: net/core/sock_reuseport.c:75
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
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
In net/core/sock_reuseport.c (ffffffff81c4f78c)
Location: net/core/sock_reuseport.c:75
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __reuseport_detach_closed_sock(struct sock *sk, struct sock_reuseport *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e046b0)
Location: net/core/sock_reuseport.c:158
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
```
**Symbols:**

```
ffffffff81e046b0-ffffffff81e04738: __reuseport_detach_closed_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __reuseport_detach_closed_sock(struct sock *sk, struct sock_reuseport *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e76f00)
Location: net/core/sock_reuseport.c:158
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
```
**Symbols:**

```
ffffffff81e76f00-ffffffff81e76f88: __reuseport_detach_closed_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __reuseport_detach_closed_sock(struct sock *sk, struct sock_reuseport *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f36ec0)
Location: net/core/sock_reuseport.c:158
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_detach_sock
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_grow
```
**Symbols:**

```
ffffffff81f36ec0-ffffffff81f36f48: __reuseport_detach_closed_sock (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
