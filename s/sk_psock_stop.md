# Function: <code>sk_psock_stop</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sk_psock_stop(struct sk_psock *psock, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4ed50)
Location: net/core/skmsg.c:784
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_close
```
**Symbols:**

```
ffffffff81a4ed50-ffffffff81a4eee3: sk_psock_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sk_psock_stop(struct sk_psock *psock, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b078c0)
Location: net/core/skmsg.c:779
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_close
```
**Symbols:**

```
ffffffff81b078c0-ffffffff81b07a53: sk_psock_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sk_psock_stop(struct sk_psock *psock, bool wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8d650)
Location: net/core/skmsg.c:799
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_close
```
**Symbols:**

```
ffffffff81c8d650-ffffffff81c8d809: sk_psock_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sk_psock_stop(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81e484f0)
Location: net/core/skmsg.c:806
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
```
**Symbols:**

```
ffffffff81e484f0-ffffffff81e48677: sk_psock_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sk_psock_stop(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81ea3ca0)
Location: net/core/skmsg.c:796
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
```
**Symbols:**

```
ffffffff81ea3ca0-ffffffff81ea3d0a: sk_psock_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sk_psock_stop(struct sk_psock *psock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81f665a0)
Location: net/core/skmsg.c:800
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
  - net/core/sock_map.c:sock_map_close
  - net/core/sock_map.c:sock_map_destroy
```
**Symbols:**

```
ffffffff81f665a0-ffffffff81f6660a: sk_psock_stop (STB_GLOBAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool wait</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
