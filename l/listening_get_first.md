# Function: <code>listening_get_first</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void *listening_get_first(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b390)
Location: net/ipv4/tcp_ipv4.c:2316
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_seek_last_pos
  - net/ipv4/tcp_ipv4.c:tcp_get_idx
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
**Symbols:**

```
ffffffff81b7b390-ffffffff81b7b471: listening_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *listening_get_first(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d09970)
Location: net/ipv4/tcp_ipv4.c:2284
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_seek_last_pos
  - net/ipv4/tcp_ipv4.c:tcp_get_idx
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
**Symbols:**

```
ffffffff81d09970-ffffffff81d09a57: listening_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *listening_get_first(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ecf1c0)
Location: net/ipv4/tcp_ipv4.c:2351
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_seek_last_pos
  - net/ipv4/tcp_ipv4.c:tcp_get_idx
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
**Symbols:**

```
ffffffff81ecf1c0-ffffffff81ecf2b1: listening_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *listening_get_first(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2de80)
Location: net/ipv4/tcp_ipv4.c:2359
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_seek_last_pos
  - net/ipv4/tcp_ipv4.c:tcp_get_idx
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
**Symbols:**

```
ffffffff81f2de80-ffffffff81f2df74: listening_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *listening_get_first(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff2a30)
Location: net/ipv4/tcp_ipv4.c:2561
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_seek_last_pos
  - net/ipv4/tcp_ipv4.c:tcp_get_idx
  - net/ipv4/tcp_ipv4.c:listening_get_next
```
**Symbols:**

```
ffffffff81ff2a30-ffffffff81ff2b24: listening_get_first (STB_LOCAL)
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
