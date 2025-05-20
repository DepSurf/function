# Function: <code>reuseport_select_sock_by_hash</code>

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
In net/core/sock_reuseport.c (ffffffff81ad1b97)
Location: net/core/sock_reuseport.c:442
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
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
In net/core/sock_reuseport.c (ffffffff81c4f404)
Location: net/core/sock_reuseport.c:442
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock *reuseport_select_sock_by_hash(struct sock_reuseport *reuse, u32 hash, u16 num_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e04210)
Location: net/core/sock_reuseport.c:528
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81e04210-ffffffff81e04295: reuseport_select_sock_by_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *reuseport_select_sock_by_hash(struct sock_reuseport *reuse, u32 hash, u16 num_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e76a60)
Location: net/core/sock_reuseport.c:528
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81e76a60-ffffffff81e76ae5: reuseport_select_sock_by_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *reuseport_select_sock_by_hash(struct sock_reuseport *reuse, u32 hash, u16 num_socks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f36a20)
Location: net/core/sock_reuseport.c:528
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_migrate_sock
  - net/core/sock_reuseport.c:reuseport_select_sock
```
**Symbols:**

```
ffffffff81f36a20-ffffffff81f36aa5: reuseport_select_sock_by_hash (STB_LOCAL)
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
