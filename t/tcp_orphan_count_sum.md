# Function: <code>tcp_orphan_count_sum</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tcp_orphan_count_sum();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5a975)
Location: net/ipv4/tcp.c:2695
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_orphan_update
Direct callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
**Symbols:**

```
ffffffff81b5f530-ffffffff81b5f5af: tcp_orphan_count_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int tcp_orphan_count_sum();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce9135)
Location: net/ipv4/tcp.c:2722
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_orphan_update
Direct callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
**Symbols:**

```
ffffffff81cedf90-ffffffff81cee01e: tcp_orphan_count_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_orphan_count_sum();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb11c0)
Location: net/ipv4/tcp.c:2822
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/proc.c:sockstat_seq_show
```
**Symbols:**

```
ffffffff81eb11c0-ffffffff81eb125b: tcp_orphan_count_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_orphan_count_sum();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0f850)
Location: net/ipv4/tcp.c:2708
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/proc.c:sockstat_seq_show
```
**Symbols:**

```
ffffffff81f0f850-ffffffff81f0f8eb: tcp_orphan_count_sum (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_orphan_count_sum();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd3a40)
Location: net/ipv4/tcp.c:2720
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_orphan_update
  - net/ipv4/proc.c:sockstat_seq_show
```
**Symbols:**

```
ffffffff81fd3a40-ffffffff81fd3adb: tcp_orphan_count_sum (STB_GLOBAL)
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
