# Function: <code>__do_once_sleepable_start</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool __do_once_sleepable_start(bool *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/once.c (0)
Location: lib/once.c:72
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
**Symbols:**

```
ffffffff820787b1-ffffffff820787c5: __do_once_sleepable_start.cold (STB_LOCAL)
ffffffff817db420-ffffffff817db474: __do_once_sleepable_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool __do_once_sleepable_start(bool *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/once.c (0)
Location: lib/once.c:72
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
**Symbols:**

```
ffffffff820f8d5c-ffffffff820f8d70: __do_once_sleepable_start.cold (STB_LOCAL)
ffffffff8181a690-ffffffff8181a6e4: __do_once_sleepable_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool __do_once_sleepable_start(bool *done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/once.c (0)
Location: lib/once.c:72
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_hash_connect
```
**Symbols:**

```
ffffffff821d687d-ffffffff821d6891: __do_once_sleepable_start.cold (STB_LOCAL)
ffffffff8185f9e0-ffffffff8185fa34: __do_once_sleepable_start (STB_GLOBAL)
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
